# Docker exercise 01


# # Clone 
```
$ git clone https://github.com/LGimenezBalanz/Docker-Kubernetes.git
$ cd ejercicio01
```

***
# # Build image 
```
$ docker build -t ejercicio01 .
```

***
# # Docker run
```
$ docker run --name ejercicio01-LG -d -p 3000:80 ejercicio01
$ start chrome http://localhost:3000/
```