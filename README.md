# Project Name: HelloWorld
This project is a simple Node.js application that prints "Hello World" to the console. The application is containerized using Docker and can be run on any machine with Docker installed.

## Getting Started
To run the application, follow these steps:

- Install Docker on your machine.
- Clone the repository to your local machine.
- Open a terminal and navigate to the project directory.
- Build the Docker image by running the following command:
-                     docker build -t helloworld .
- Once the image is built, run the container using the following command:
-                     docker run -p 8080:8080 helloworld
## Technologies Used
- Node.js
- Docker
