## Definir puertos

```bash
docker run -p 8080:80 httpd
```

* `-p` Establece un mapping entre los puertos de la máquina anfitrión y la máquina destino
* Si necesitamos múltiples puertos, podemos encadenar varios parámetros `-p`