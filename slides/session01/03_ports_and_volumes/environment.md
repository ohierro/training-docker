## Definir variables de entorno

```bash
docker run -e VARIABLE_X=test 8080:80 httpd
```

* `-e` Indica variables del sistema a definir en el contenedor
* Si necesitamos múltiples puertos, podemos encadenar varios parámetros `-e`