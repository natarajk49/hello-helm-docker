# Node.JS web application with Express.JS #

## Pre-requisites ##

- `npm install -g gulp`

## Docker image build instructions ##
Execute `gulp dist` and then `docker build -t <image-name>`

## Running instructions
Assuming you named the image `mynodeapp`, you can run a container based off t                                                                                           his
image using  `docker run --rm -p 80:3000 mynodeapp:latest`.

## Pulling from Docker Hub
This image can be pulled from Docker Hub using `docker pull rubixcubin/simple                                                                                           -node-express:latest`





   Build:
         sudo npm install -g gulp
        Docker build:
          docker build -t gulp .
          docker images
          docker tag  gulp:latest mynodeapp:latest

    helm upgrade --install -f hello/values.yaml hello ./hello -n hello
        kubectl get all -n hello
        kubectl get ing -n hello
        curl  http://helloworld.iffdev.com/
