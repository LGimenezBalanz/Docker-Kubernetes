# Docker exercise 06


## Build image 
```
$ docker build -t ejercicio6-lg .
```

## Docker run
```
$ docker run --name ejercicio6-lg -d -p 3000:8080 ejercicio6-lg
$ start chrome http://localhost:3000/
```

## Link a la imagen
lgimenez98/password-api:2.0.0
https://hub.docker.com/layers/password-api/lgimenez98/password-api/2.0.0/images/sha256-474fcffc3058f375204f33c74e4e3a7d0d7046ba66a3065d255d3dc5febe6451?context=explore