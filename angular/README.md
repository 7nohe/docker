# Dockerfile for ionic-cli environment


## Build

```
$ docker build -t angular/YOUR_IMAGE_NAME .
```


## Run

```
$ docker run -p 4400:4200 -dit --name YOUR_APP_NAME -v YOUR_PROJECT_PATH:/code angular/YOUR_IMAGE_NAME
```

