## Estructura

* services: Cada uno de los services que queremos agrupar
* build | image: Si queremos que el contenedor se construya a partir de una imagen o de un Dockerfile
* ports: Puertos que expondrá la aplicación (equivalente a -p)
* environment: Lista de variables de entorno (equivalente a -e)
* volumes: Lista de volúmenes a montar (equivalente a -v)