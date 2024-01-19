Introduction:

![Alt text](image.png)

![Alt text](image-1.png)

![Alt text](image-2.png)

![Alt text](image-3.png)

![Alt text](image-4.png)

![Alt text](image-5.png)

![Alt text](image-6.png)

Architectural design:

So first we are going to fetch in our source code from our Git repository and we are going to do the entire Docker workflow. First we are going to write Dockerfile for the services that needs customization. So we have nginx, TomCat, and MySQL. So we have to write three Dockerfiles.
Once we have written Dockerfile in our source code, then we are going to use a Docker Build command which will get executed on our Docker engine. In our Dockerfile, we should have mentioned the base image. This base images will be pulled from Docker Hub. So TomCat, nginx, and MySQL, these are three images that we're going to pull and customize them.
So Docker Build command is going to read the Dockerfile, build our image. Once our images are ready, we're going to use a Docker Compose. We'll mention all the containers with the images and then we are going to test it. Once it checks out fine, then we are going to push our Docker images, the customized Docker images, to Docker Hub in our own account. So that's the entire Docker workflow that we are going to do.
