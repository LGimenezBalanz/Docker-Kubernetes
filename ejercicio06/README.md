# Docker exercise 04


## Build image 
```
$ docker build -t ejercicio6-lg . --build-arg JAR_FILE=./passwordapi.jar
```

## Docker run
```
$ docker run --name ejercicio6-lg -d -p 3000:8080 ejercicio6-lg
$ start chrome http://localhost:3000/
```

## Link a la imagen
https://hub.docker.com/r/lgimenez98/password-api