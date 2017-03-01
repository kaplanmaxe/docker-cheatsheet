# Docker Cheat Sheet

##### Start new docker container:
`docker run -ti ubuntu bash`

##### Find all containers:
`docker ps`

##### Find last exited container
`docker ps -l`

##### Convert container to image
`docker commit <CURRENT_NAME> <NEW_NAME>`

##### "SSH" into container
`docker exec -ti <TEMP_NAME> bash`

##### Run image and open bash
`docker run -ti <NAME> bash`

TO KEEP RUNNING

`docker run -d -ti <NAME> bash`

##### View container logs
`docker logs <NAME>`

##### Build from docker file
`docker build -t <NEW_CONTAINER_NAME> .`
