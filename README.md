# Nextcloud docker installation howto 
This howto provides the necessary instructions to deploy the Nextcloud with the official docker image MariaDB and Linuxserver/swag Letsencrypt nginx proxy
## Cloning the repository 
Execute the following command to clone the repository 
```
git clone https://github.com/dasunwnl/nextcloud.git
```
## Start the containers
Execute the following command to start the containers in the background 
```
docker-compose up -d
```
## To view that the containers started properly 
Execute the following command
```
docker-compose ps
```
## To debug the containers starting
Execute the following command to observe the container logs for debugging the initial creation of containers
```
docker-compose logs -f
```
## To delete the containers 
Execute the following commands
```
docker-compose down
```
