# Docker in Docker service 

### Info:

Enables your container to run docker inside docker.
More Info: https://hub.docker.com/r/library/docker/

### Usage

Link your container against this one.
Set the environment variabe `DOCKER_HOST` in your container to `tcp://<linkname>:2375`
Install docker-engine 1.10.3 in your container and run `docker run hello-world`
