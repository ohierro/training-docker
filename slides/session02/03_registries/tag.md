## Publicar imágenes

Primero necesitamos etiquetar la versión que queremos publicar

```bash
docker tag <imagen-local> <registry/imagen-remota>
```

A continuación, hacer un `push`

```bash
docker push <registry/imagen-remota>
```

