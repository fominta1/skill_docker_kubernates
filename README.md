> Modified repo initially created by Nana Janashia here: https://gitlab.com/nanuchi/developing-with-docker/-/tree/feature/k8s-in-hour

## demo app - developing with Docker

This demo app shows a simple user profile app set up using 
- index.html with pure js and css styles
- nodejs backend with express module
- mongodb for data storage

All components are docker-based

#### To start as K8s pod
    docker build -t xelorr/k8s-demo-app:v1.0 .
    docker push xelorr/k8s-demo-app:v1.0



