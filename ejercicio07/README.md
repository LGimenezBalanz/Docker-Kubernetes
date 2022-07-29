# Docker exercise 07


## Up
```
$ docker-compose -f docker-compose-jobvacancy.yml up
```

¿Cuántos contenedores se están ejecutando? 

    Se ejecutan don contenedores,  ejercicio07_web_1 y ejercicio07_db_1

¿Cuáles son las imágenes en las que están basados los mencionados contenedores?:

    El contenedor ejercicio07_web_1 en la imagen nicopaez/jobvacancy-ruby:1.3.0 y
    el contenedor ejercicio07_db_1 en postgres:14.4-alpine

¿Puedes leer el docker-compose-jobvacancy.yml y describir lo que hace cada una de sus lineas?
Dado que cada contenedor corre en forma aislada ¿Cómo es posible que esos contenedores se vean entre sí?:

    - image: se especifica la imagen con la cual se creará el contenedor
    - environment: se agregan las variables de entorno, en este caso el puerto, el ambiente y la url de la base de datos para el contenedor "web" y la contraseña para la db en el contenedor "db"
    - links: se linkea el contenedor con alguno de los otros servicios
    - ports: se especifica el mapeo de los puertos del host y el contenedor
    - depends_on: se definden las dependencias entre los servicios