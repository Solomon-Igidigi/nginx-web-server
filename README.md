Dockerized Web Server

This project demonstrates how to containerize a web server using Docker.

Prerequisites

- Docker installed on your machine
- Basic understanding of Docker and containerization

Getting Started

1. Clone this repository: git clone https://github.com/Solomon-Igidigi/nginx-web-server.git
2. Navigate to the project directory: cd nginx-web-server
3. Build the Docker image: docker build -t my-nginx-web-server .
4. Run the Docker container: docker run -p 8080:80 my-nginx-web-server

Usage

1. Open a web browser and navigate to http://localhost:8080
2. You should see the web server's default page

Dockerfile Explanation

The Dockerfile in this project uses the following instructions:

- FROM: Specifies the base image (e.g., nginx:latest)
- COPY: Copies files from the host machine to the container
- EXPOSE: Exposes a port from the container to the host machine
- CMD: Specifies the default command to run when the container starts
