## Desplegando un servicio

```bash
docker service create --replicas 1 --name helloworld alpine ping docker.com
```

Para visualizar los servicios creados
```bash
docker service ls
```

Mostrar información sobre el servicio
```bash
docker service inspect --pretty helloworld
```

note:
Probar a attacharnos al servicio y matarlo para ver cómo se vuelve a levantar
