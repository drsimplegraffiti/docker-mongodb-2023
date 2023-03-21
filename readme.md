#### Docker up
> docker compose up

#### Stop all running containers
> docker stop $(docker ps -a -q)

#### build and rebuild images - Always use this command when you make changes to the dockerfile or docker-compose.yml
> docker-compose up --build 


