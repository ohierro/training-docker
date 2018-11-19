## Hello world compose

docker-compose.yml

```yml
version: '3'
services:
    web:
        image | build:
        ports:
            - 80:80
        environment:
            - ENVIRONMENT_VAR=value
```

note:
- Montar el servicio de nginx como imagen y como compilación