## Ejecución de comandos

ENTRYPOINT: Indica el comando a ejecutar por defecto en la imagen

```Dockerfile
ENTRYPOINT ["executable", "param1", "param2"] (exec form, preferred)
ENTRYPOINT command param1 param2 (shell form)
```

note:
- Probar a poner un bash en nuestra imágen