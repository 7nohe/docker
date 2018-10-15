# Dockerfile for vue-cli environment


## Build

```
$ docker build -t nuxt/YOUR_IMAGE_NAME .
```


## Run

```
$ docker run -p 8010:8080 -dit --name YOUR_APP_NAME -v YOUR_PROJECT_PATH:/code nuxt/YOUR_IMAGE_NAME
```
