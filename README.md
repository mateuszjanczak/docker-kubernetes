## Docker

### Build the app’s container image

```sh
$ docker build . -t mateuszjanczak/example-app
```

### Start an app container

```sh
$ docker run -p 8080:8080 -d mateuszjanczak/example-app
```

### Push the image

```sh
$ docker image push mateuszjanczak/example-app
 ```