
  <div>
    <img src="https://img.shields.io/badge/-Node_JS-black?style=for-the-badge&logoColor=white&logo=nodedotjs&color=339933" alt="nodedotjs" />
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Docker-black?style=for-the-badge&logoColor=white&logo=docker&color=2496ED" alt="docker" />
    <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="mongodb" />
    <img src="https://img.shields.io/badge/-Vite-black?style=for-the-badge&logoColor=white&logo=vite&color=646CFF" alt="vite" />
  </div>

  <h3 align="center">Docker Learning</h3>

   <div align="center">
     Learn how to Dockerize various applications step by step with our detailed explanation
    </div>
</div>

<br />

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
6. 📦 [Starter Kit](#starter-kits)
7. 🕸️ [Code Snippets](#code-snippets)
8. 🚀 [More](#more)

<br />

## 🚨 Tutorial

This repository contains the code corresponding to an in-depth tutorial available on our YouTube channel, <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a>. 

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!

<a href="https://youtu.be/GFgJkfScVNU?feature=shared" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>

## <a name="introduction">🤖 Introduction</a>

Learn the process of containerizing frontend, backend, and database applications built with diverse tech stacks like React, Vue, Svelte, or any Vite projects. 
Additionally, it covers examples of the containerization of complete full-stack applications, including MERN setups or the popular Monorepo full-stack applications using Next.js 14+. 

This repository contains the corresponding code for all these dockerized applications using the latest Docker features, including docker-compose watch and init.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 27k+ members. It's a place where people help each other out.

<a href="https://discord.com/invite/n6EdbFJ" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/618f4872-1e10-42da-8213-1d69e486d02e" /></a>

## <a name="tech-stack">⚙️ Tech Stack</a>

- Docker
- Node.js
- React.js
- Vite
- MongoDB
- Express.js
- Next.js
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Fundamentals of Docker**: Understand the fundamentals of Docker, its purpose, and advantages.

👉 **Managing Images and Containers with Docker Compose**: Explore Docker Compose for orchestrating multiple images and containers efficiently.

👉 **Latest Docker Features**: Learn new features such as docker init, docker scout, and docker compose watch for enhanced development workflows.

👉 **Working with Volumes**: Learn how to use volumes for persistent data management in Docker containers

👉 **Port Mapping with Network**: Implement port mapping using Docker's networking capabilities

👉 **Dockerizing React Applications with Vite**: Step-by-step guide on Dockerizing React applications built with Vite.

👉 **Dockerizing Vite Applications (Vue or Svelte)**: Extend the knowledge to Dockerizing Vite applications, supporting Vue or Svelte frameworks.

👉 **Dockerizing Full Stack Applications**: Dockerize a complete MERN stack application, covering frontend, backend, and database.

👉 **Dockerizing Monorepo Full Stack Applications (Next.js 14+)**: Explore Dockerizing Monorepo full-stack applications using the latest features of Next.js (version 14 and above).

👉 **Publishing Docker Images**: Learn the steps to publish Docker images, making your applications accessible to a broader audience.

...and much more, covering the best practices and usage of different commands in 🐳

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)
- [Docker](https://www.docker.com/products/docker-desktop/)
- [MongoDB Compass](https://www.mongodb.com/products/tools/compass)

**Cloning the Repository**

```bash
git clone https://github.com/your-username/your-project.git
cd your-project
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

For a few specific applications, we require environment variables. I've included a sample .env.example file for these essential projects. 
However, one crucial element needed for these projects is,

```env
DB_URL=
```

For full stack applications, we'll be using MongoDB as a database. So do create an account on [MongoDB Atlas](https://www.mongodb.com/) as well as 
install [MongoDB Compass](https://www.mongodb.com/products/tools/compass) for creating local database instance for the project. 

**Running the Project**

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

