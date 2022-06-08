Project to develop a Node.js/MongoDB application using Helm charts
// Write a Docker file to build a node_app along with source code and corresponding configuration files
- Using alpine as a base image to build a node_app
docker build -t your_dockerhub_username/node_app .
docker login -u your_dockerhub_username
docker push your_dockerhub_username/node_app