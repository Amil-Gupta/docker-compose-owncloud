# docker-compose-owncloud
Infrastructure-as-code docker-compose.yml file for using owncloud cloud-storage on your computer.
Uses owncloud docker image along with mysql version 5.7 docker image for databases-creation.
Uses docker volumes to permanently store data and prevent data-loss due to server crash or shutdown.
Automatically restarts containers after a server-crash.
Might require security and firewall bypass permissions to function properly.
