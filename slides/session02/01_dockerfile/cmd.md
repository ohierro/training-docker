## Ejecución de comandos

CMD: Indica el comando a ejecutar por defecto en la imagen

```Dockerfile
CMD ["executable", "param1", "param2"] (exec form, preferred)
CMD command param1 param2 (shell form)
```

- ENTRYPOINT se ejecutará siempre
- CMD es posible sustituirlo por un comando propio

note:
- Probar a ejecutar una imagen con CMD y ENTRYPOINT y bash como comando