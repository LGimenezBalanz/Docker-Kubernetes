# Docker exercise 04


## Build image 
```
$ docker build -t ejercicio4LG . --build-arg JAR_FILE=./passwordapi.jar
```

## Docker run
```
$ docker run --name ejercicio4LG -d -p 3000:8080 ejercicio4LG
$ start chrome http://localhost:3000/
```

## Link a la imagen
https://hub.docker.com/r/lgimenez98/password-api