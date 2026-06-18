This project demonstrates the installation and configuration of Docker on a local machine, along with pulling and running container images from Docker Hub. The experiment focuses on understanding the fundamentals of containerization by creating Docker containers using popular Linux-based images such as Ubuntu and Alpine.
The main objective of this project is to:

Install and configure Docker Desktop on a local system.
Verify the Docker installation.
Pull container images from Docker Hub.
Create and run Docker containers.
Access and interact with containers through the command-line interface.

Docker Desktop installation and setup.
Verification of Docker installation using Docker CLI.
Downloading images from Docker Hub.
Running interactive containers.
Exploring containerized Linux environments.
Understanding basic Docker commands and workflows.

Docker Desktop
Docker Hub
Ubuntu Container Image
Alpine Linux Container Image
Command Line Interface (CLI)

System Requirements
Operating System: Windows 10/11, macOS, or Linux
RAM: Minimum 4 GB (8 GB Recommended)
Internet Connection: Required for downloading Docker images
Virtualization Technology (VT-x/AMD-V) enabled in BIOS

Download and install Docker Desktop from the official Docker website.

Run the following command:

docker --version

Pull Docker Images

Download the Alpine Linux image:

docker pull alpine

Download the Ubuntu image:

docker pull ubuntu

Run a Docker Container

Launch an interactive Ubuntu container:

docker run -it ubuntu

Project Workflow
Install Docker Desktop.
Verify Docker installation.
Connect to Docker Hub.
Pull required container images.
Create and run containers.
Access the container shell.
Explore and execute commands within the container environment.
