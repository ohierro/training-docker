## Definir volúmenes

```bash
docker run -p 8080:80 -v <path absoluto>:/usr/local/apache2/htdocs httpd
```
* `-v` Establece un mapping entre directorios de la máquina anfitrión y la máquina destino
* Si necesitamos varios directorios, podemos encadenar varios parámetros `-v`