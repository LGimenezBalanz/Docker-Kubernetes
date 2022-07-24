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
lgimenez98/password-api:1.0.0
https://hub.docker.com/layers/password-api/lgimenez98/password-api/1.0.0/images/sha256-f6cfff23abc04a9af7fd6aafcf8d82e4b61213719a7e0d42d2c737a343788764?context=explore