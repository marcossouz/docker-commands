<h1 align="center"> Docker commands </h1>

<p align="center"> Repository created for docker build scripts </p>

# Content

> criate container postgres 
> - `sudo docker run --name postgres -p 5432:5432 -e POSTGRES_PASSWORD=mypass -d postgres:latest` 

> criate container elasticsearch
> - `docker run -d --name elasticsearch -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" elasticsearch:7.10.1`

