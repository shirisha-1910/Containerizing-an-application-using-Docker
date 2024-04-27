# Containerizing an application using Docker

This project aims to containerize an application using Docker, providing an efficient and portable deployment solution. Below are the steps involved in the process:

## Dockerfile Creation

1. **Define Dockerfile**: Create a `Dockerfile` to specify the environment and dependencies required to run the application.
2. **Install Dependencies**: Use appropriate package managers to install necessary dependencies within the Docker image.
3. **Set Working Directory**: Define the working directory within the Docker image where the application code will be placed.
4. **Copy Application Files**: Copy the application files (such as HTML, CSS, JavaScript) into the Docker image.
5. **Expose Ports**: Expose any necessary ports required for communication with the application.

[Dockerfile](Dockerfile)

## Application Code

The source code for the application can be found [Link to CFK Page](CFK%28temp%20converter%29/temp.html).

## Building the Docker Image

1. **Build Image**: Use the `docker build` command to build the Docker image from the `Dockerfile`.
2. **Tag Image**: Tag the built image with a relevant name and version for easy identification.
3. **Push to Docker Hub/ECR**: Optionally, push the built image to Docker Hub or Amazon ECR for sharing and deployment.

## Running the Docker Container

1. **Start Container**: Use the `docker run` command to start a container from the built Docker image.
2. **Port Mapping**: Map any required ports from the container to the host system using the `-p` flag.
3. **Volume Mounting**: Optionally, mount volumes to persist data between container restarts using the `-v` flag.

## Accessing the Application

Once the Docker container is running, access the application through the specified ports on the host system.

## End of Deployment

The application is now successfully deployed and accessible within the Docker container.



