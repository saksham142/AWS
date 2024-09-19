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

Key Features:

   - High Performance: Nginx is designed to handle a large number of concurrent connections efficiently. It uses an event-driven architecture, which allows it to serve multiple requests without consuming a lot of resources.

   - Reverse Proxy: It can act as a reverse proxy, forwarding client requests to other servers. This is useful for load balancing and increasing security.

   -  Load Balancing: Nginx can distribute incoming traffic across multiple servers to ensure no single server is overwhelmed, improving reliability and performance.

   -  Static Content Serving: Nginx excels at serving static files (like images, CSS, and JavaScript) quickly and efficiently.

   -  SSL/TLS Support: It provides built-in support for secure connections via SSL/TLS, making it suitable for serving HTTPS traffic.

   -  URL Rewriting: Nginx can rewrite URLs, which is useful for SEO and maintaining user-friendly links.

   -  Flexible Configuration: Its configuration files are simple and allow for complex setups, including virtual hosting and URL routing.

   - WebSockets Support: Nginx can handle WebSocket connections, making it a good choice for real-time web applications.


# How to Install NGINX

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
In this tutorial, we’ll show you how to install NGINX on Linux. Open your Linux machine and run an update using the command below:

    sudo apt-get update
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Next, run this command: 

    sudo apt-get install nginx
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Then, enable your firewall with the following: 

    sudo ufw enable
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
To verify NGINX is installed, run the following:

    nginx -v
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
You can run the command below to find out if NGINX is running:

    sudo ufw status
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
After running this command, you should see the following:

    status: active
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
To check whether your NGINX server is working fine, run the following:

    sudo systemctl status nginx
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


