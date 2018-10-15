# Dockerfile for ionic-cli environment


## Build

```
$ docker build -t ionic/YOUR_IMAGE_NAME .
```


## Run

```
$ docker run -p 8100:8000 -dit --name YOUR_APP_NAME -v YOUR_PROJECT_PATH:/code ionic/YOUR_IMAGE_NAME
```
