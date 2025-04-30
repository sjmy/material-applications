# material-applications #

This repository contains example applications for the course DevOps with Docker.


## Exercise 3.1: Your pipeline ##

docker-compose.yml is found in the watchtower folder.

<code>docker compose up</code> will run the express-app container and the watchtower container. Changes pushed to the repo will automatically push a new image to Docker Hub, pull the new image, and update the running express-app container.