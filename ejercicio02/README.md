# Docker exercise 02

# # Description
 Descargar imagen nicopaez/pingapp:3.0.0
```
$ docker pull nicopaez/pingapp:3.0.0

```

Etiquetar imagen
```
$ docker tag 5021b0410677 lgimenez98/pingapp:3.0.0

```

Login Docker Hub
```
$ docker login
```
Publicar imagen en cuenta de Docker Hub
```
$ docker push lgimenez98/pingapp:3.0.0
```
Comando para descargar imagen publicada
```
$ docker pull lgimenez98/pingapp:3.0.0
```
