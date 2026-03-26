
#set the base image to create the images from react app
FROM node:20-alpine


#create a user with permission to run the app
# -S -> Create a system user
# -G -> Add the user to a group
# -D -> Don't create a home directory for the user
# this is done to avoid runing the app as root user which is a security risk
RUN addgroup app && adduser -S -G app app

#set the user to run th app
USER app

#set the working directory to /app
WORKDIR /app


#copy the package.json file to the working directory
#This is done before copying the rest of the files to take advantage of Docker's caching mechanism. If the package.json file hasn't changed, Docker will use the cached layer for installing dependencies, which can speed up the build process.
COPY package.json ./

#install the dependencies
#to avoid running npm install every time we build the image, we can use the --only=production flag to install only the production dependencies. This is done to reduce the size of the image and to avoid installing unnecessary dependencies.
USER root


#change the user back to app user to run the app
# -R -> Change the ownership of the files to the app user and group
# chown is used to change the ownership of the files to the app user and group. This is done to avoid permission issues when running the app as a non-root user.
RUN chown -R app:app .


#change the user back to app user to run the app
USER app

#copy the rest of the files to the working directory
COPY . .

#expose the port 3000 to the outside world
EXPOSE 5173

#command to run the app
CMD npm run dev
