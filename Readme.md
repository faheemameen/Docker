### What is Docker?

- Docker is an open platform for developing, shipping, and running applications.

- It enables developers to package applications into containers, which are standardized units of software that include everything the software needs to run

#### Docker image:

- Docker images are read-only templates that contain instructions for creating a container. A Docker image is a snapshot or blueprint of the libraries and dependencies required inside a container for an application to run

#### Docker Container:

- A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another

### What is Dockerfile

- A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image.

---

- To build the image run this command:

`docker build -t img:1.0 .`

- -t is used to give the name and version of image

- To run the container of image run this command

`docker run -p 8000:8000 img:1.0` (in interactive mode)

`docker run -d -p 8000:8000 img1.0` (in detached mode)
