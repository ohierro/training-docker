## Redes en docker

Docker gestiona 'redes internas' para los contenedores
Se encarga de hacer el mapeo de puertos entre host y container

* Tipos

    * bridge
    * host
    * overlay
    * macvlan
....

note:
bridge: recomendad y por defecto
host: remove network isolation between the container and the Docker host

Comandos
* docker network ls