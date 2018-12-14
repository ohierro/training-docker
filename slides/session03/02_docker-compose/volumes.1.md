## Volúmenes

Los volúmenes nos permiten definir un storage persistente sin necesidad de tener que mapear un directorio físico

```yaml
volumes:
    db_data:
```

Nos permite mapear directorios a dichos volúmenes

```yaml
services:
    db:
        volumnes:
            - db_data:/....
```

