# outrun-docker
Outrun Game - Docker App (2024)


## Download the code and Build the container
```bash
git clone https://github.com/Juli-BCN/outrun.git
cd outrun
docker build -t outrun .
docker images
```


## Run, Test & Stop the Docker container
```bash
docker run -d -p 80:80 outrun
curl -L http://localhost
docker ps
```bash

> :eyeglasses: docker stop *CONTAINER_ID*