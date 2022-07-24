# Docker exercise 05

## HEALTHCHECK
La instrucción HEALTHCHECK se utiliza para definir una verificación del estado de un contenedor, poniendo a prueba su funcionamiento. El contenedor tendrá un nuevo estado llamado "health status" que tendrá valor "healthy" en caso de una verificación exitosa o "unhelthy" en caso contrario. Se puede definir:
* El intervalo entre cada control de salud (30 segundos por defecto): --interval=35s
* El tiempo límite que debe durar este proceso para no considerarse "unhealthy": --timeout=4s
* La cantidad de reintentos, y en caso de excederse se considera fallido


## ONBUILD
La instrucción ONBUILD define otras instrucciones que no afectará la imagen donde se definen, sino que serán ejecutadas en otras imágenes que utilicen esta primera como base. Docker inspecciona los metadatos de las imágenes padres para buscar estas instrucciones, y en caso de algún fallo se abortará la compilación.


## VOLUME
La instrucción VOLUME se utiliza para definir un mount point como volumen de Docker para cada uno de los contenedores construidos a partir de esa imagen. Esto con el objetivo de guardar los cambios de un determinado directorio de sus contenedores.