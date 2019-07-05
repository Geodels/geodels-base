# geodels-base

Base Docker Container

https://hub.docker.com/u/geodels/


### Local installation

*Python 2 version:*

```
docker build -t geodels/geodels-base:latest -f Dockerfile .
```

*Python 3 version:*
```
docker build -t geodels/geodels-base:python3 -f Dockerfile-python3 .
```

### Pushing the containers registry

```
docker login -u $DOCKER_HUB_USER -p $DOCKER_HUB_PASSWORD
```

```
docker push geodels/geodels-base:latest
docker push geodels/geodels-base:python3
```
