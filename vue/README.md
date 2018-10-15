# Dockerfile for vue-cli environment


## Build

```
$ docker build -t vue/YOUR_IMAGE_NAME .
```


## Run

```
$ docker run -p 8010:8080 -dit --name YOUR_APP_NAME -v YOUR_PROJECT_PATH:/code vue/cli
```
