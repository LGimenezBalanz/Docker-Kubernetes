# Docker exercise 04


## Build image 
```
$ docker build -t ejercicio4-lg . --build-arg JAR_FILE=./passwordapi.jar
```

## Docker run
```
$ docker run --name ejercicio4-lg -d -p 3000:8080 ejercicio4-lg
$ start chrome http://localhost:3000/
```

## Link a la imagen
https://hub.docker.com/r/lgimenez98/password-api