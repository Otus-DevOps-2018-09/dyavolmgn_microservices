
# dyavolmgn_microservices
dyavolmgn microservices repository

### Docker-3
---
## Задания:
docker run -d --network=reddit --network-alias=post_db --network-alias=comment_db mongo:latest
docker run -d --network=reddit --network-alias=post dyavolmgn/post:1.0
docker run -d --network=reddit --network-alias=comment dyavolmgn/comment:1.0
docker run -d --network=reddit -p 9292:9292 dyavolmgn/ui:1.0


### Docker-2
---
```
gcloud init
gcloud auth
```
 - install [Docker Machine]
 - Create docker host
 - Create docker image
 - docker push image



### Docker-1
---
Задание:
 # cread docker image

Задание со *
 # docker inspect
