# sdlc-docker-application

Github repo
https://github.com/jakezhong/sdlc-docker-application

Docker Hub repo
https://hub.docker.com/r/jakezhong/sdlc-docker-application

## Step 1: Initialize files and build an image
docker build . -t jakezhong/sdlc-docker-application

## Step 2: Docker run the image
docker run -p 49160:8080 -d jakezhong/sdlc-docker-application

## Step 3: Create a repository on Docker Hub and push the image to it
docker push jakezhong/sdlc-docker-application
