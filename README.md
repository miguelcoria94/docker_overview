# docker_overview

Installing docker give you the client and daemon 

Client makes the API calls to daemon

Daemon implements the Docker Remote API

'docker run' starts a new container

Docker Hub is the default public registry

The daemon will pull images that it doesn't already have

# Container and images

images - stopped containers

containers - running images

NOTE: You can pull images from docker hub using 'Docker Pull' - This will pull the latest images

When you create a container it goes to running state and started and stopped

docker start

docker stop

docker rm


docker run <images>

Daemon does  all the heavy listening 

Default registry is the Docker Hub

#Swarm mode and microservices

#Swarmmode - native clustering

a swarm is a native clustering engine

Manager nodes maintain the swarm and only one is the leader

