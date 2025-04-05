# 5.1P: Containerisation of a simple web application using Docker
containerize a Node.js web application using Docker and Docker Compose. 
## Part I: Containerizing the Application
### Step-1 Creating base folder and Node.js Environment
npm init -y
npm install express
### Step-2 Creating Docker file
Create a Dockerfile in the root of your project
### Step-3 Build Docker image
docker build -t my-node-app .
### Step-4 Create Compose file
### Step-5 Pushing file
After building the Docker image and creating the Compose file, the next step is to push the Docker image to a container
1.	docker tag my-node-app akanksha0712/my-node-app
2.	docker push akanksha0712/my-node-app
## Part II: Implementing Container Health Checks
Health checks monitor the status of your application, ensuring it is functioning correctly. 
In docker-compose.yml file, under the app service, we add the healthcheck configuration
## Conclusion
Using Docker and Docker Compose, we have successfully containerized the Node.js application. The addition of health checks ensures that the application is monitored and maintained properly.
