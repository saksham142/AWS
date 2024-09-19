# DOCKERS

<p align="center">
  <img src= https://github.com/saksham142/starting-ec2/blob/cd28260524bbf1012c67118dda918f1b60715fdf/1_AFo8ylyGvmAzIlKvsQiT-A.jpg alt="Description" />
</p>   


Docker is an open-source platform that enables developers to automate the deployment, scaling, and management of applications using containerization. Containers package an application and its dependencies into a single, lightweight unit, ensuring consistency across various environments. Docker uses images—read-only templates—to create these containers, which are isolated but share the host OS kernel. With tools like Docker Compose, users can define and manage multi-container applications easily. Docker Hub serves as a registry for sharing and storing images. Overall, Docker enhances portability, efficiency, and scalability, streamlining the application development lifecycle

### Key Components of Docker:


- Docker Engine: The core software that runs and manages containers. It consists of a server (the Docker daemon), a REST API, and a command-line interface (CLI).

- Images: A Docker image is a lightweight, standalone, and executable package that includes everything needed to run a piece of software (code, runtime, libraries, environment variables). Images are read-only templates used to create containers.

- Containers: A container is a running instance of a Docker image. It includes the application code, libraries, and settings, and operates in an isolated environment.

- Dockerfile: A text file that contains instructions for building a Docker image. It specifies the base image, application dependencies, and commands to run the application.

- Docker Hub: A cloud-based registry service where you can find, store, and share Docker images. It includes official images for various software and allows users to publish their own images.

## HOW TO INSTALL DOCKER:
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Update package index

       sudo apt update
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
- Install required packages

      sudo apt install apt-transport-https ca-certificates curl software-properties-common
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Add Docker’s official GPG key

      curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Add Docker's stable repository

      sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Update the package index again

      sudo apt update
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Install Docker

      sudo apt install docker-ce
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# NGINX


<p align="center">
  <img src= https://github.com/saksham142/AWS/blob/2d6b245c98cc9ba5aea7e91a5af5a27c777bebb4/1_9R59VNTAanVTzFefjOXqvg.png alt="Description" />
</p>   

Nginx (pronounced "engine-x") is a high-performance web server, reverse proxy, and load balancer. Designed for efficiency, it uses an asynchronous, event-driven architecture, allowing it to handle thousands of simultaneous connections with low memory usage. Nginx excels at serving static content and can distribute traffic across multiple servers, enhancing reliability and speed. It supports SSL/TLS for secure connections and modern protocols like HTTP/2 and gRPC. Configuration is straightforward, using text files to define server and location blocks. Overall, Nginx is a popular choice for high-traffic websites and applications due to its scalability and performance.

