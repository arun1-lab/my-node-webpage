# My Node.js Web Page

## Description
Welcome to my Node.js web application! This project is built using Node.js and Express 

## Table of Contents
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Running with Docker](#running-with-docker)
- [Project Structure](#project-structure)


## Getting Started

### Prerequisites
Before you begin, make sure you have the following installed:
- **Node.js** (version 14 or later)
- **npm** (Node Package Manager)
- **Docker** (if you want to run it in a container)

### Installation
To get your local copy up and running, follow these steps:

1. **Clone the Repository**: 
   Open your terminal and run:
   ```bash
   git clone https://github.com/arunt98/my-node-webpage.git
Navigate into the Project Directory:
cd my-node-webpage

Install Dependencies:
npm install


To start the application, use the following command:
npm start

Then, open your web browser and go to http://localhost:3000 to see the welcome page in action!

Build the Docker Image:
docker build -t my-webpage .

Run the Docker Container:
docker run -d -p 3000:3000 my-webpage
Access the Application: Open your browser and go to http://<your-ec2-public-ip>:3000.

Project Structure

my-node-webpage/
├── Dockerfile
├── package.json
├── package-lock.json
├── server.js
├── public/
│   ├── index.html
│   └── styles.css
└── README.md

File Descriptions
Dockerfile: Contains instructions for building the Docker image.
package.json: Lists the dependencies and scripts for the project.
server.js: The main entry point for the Node.js application.
public/: This folder holds static files like HTML and CSS.
