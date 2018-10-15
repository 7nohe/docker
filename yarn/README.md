# Dockerfile for vue-cli environment


## Build

```
$ docker build -t yarn/YOUR_IMAGE_NAME .
```


## Run

```
$ docker run -p 3020:3000 -dit --name YOUR_APP_NAME -v YOUR_PROJECT_PATH:/code YOUR_IMAGE_NAME
```
