# Docker-Projects
Some short projects to get used to using docker and some other tools.

## Containarize and Run an App
Project 1
Objective: Create a container to run a simple app in your local network.
 - Create a simple single-file app (python FastAPI)
 - write a Dockerfile to package it into a lightweight container

## Reverse Proxy and SSL Automation (Nginx)
Project 2
Objective: Run multiple isolated web services on a single server, routing traffic based on domain names/subdomains using a reverse proxy container.
 - Make a docker-compose.yml file to run the reverse proxy service and create a shared docker network
 - Connect app containers to the proxy throgh Nginx Proxy Manager and enable SSL
