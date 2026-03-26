
#set the base image to create the images from react app
FROM node:20-alpine


# RUN addgroup app && adduser -S -G app app
# USER app

#set the working directory to /app
WORKDIR /app


#copy the package.json file to the working directory
#This is done before copying the rest of the files to take advantage of Docker's caching mechanism. If the package.json file hasn't changed, Docker will use the cached layer for installing dependencies, which can speed up the build process.
COPY package*.json ./

# USER root
# RUN chown -R app:app .
# USER app

#copy the rest of the files to the working directory
RUN npm install
COPY . .
EXPOSE 5173
CMD npm run dev
