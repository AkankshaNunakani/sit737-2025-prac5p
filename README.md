# 5.1P: Containerisation of a simple web application using Docker
containerize a Node.js web application using Docker and Docker Compose. 
## Part I: Containerizing the Application
### Step-1 Creating base folder and Node.js Environment
The steps include creating a new directory and initializing the project using npm.
### Step-2 Creating Docker file
The Dockerfile defines the application’s environment and the instructions needed to build the Docker image. 
### Step-3 Build Docker image
The Docker image is built based on the Dockerfile created in the previous step. The image will contain all the necessary dependencies and configurations.
### Step-4 Create Compose file
The Docker Compose file is used to define and run multi-container Docker applications and then test the application.
### Step-5 Pushing file
After building the Docker image and creating the Compose file, the next step is to push the Docker image to a container
1.	docker tag my-node-app akanksha0712/my-node-app
2.	docker push akanksha0712/my-node-app
## Part II: Implementing Container Health Checks
Health checks monitor the status of your application, ensuring it is functioning correctly. 
In docker-compose.yml file, under the app service, we add the healthcheck configuration

