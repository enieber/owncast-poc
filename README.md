# Owncast poc

Poc de como usar owncast.


## Rodar com podman

```sh
podman run -v `pwd`/data:/app/data -p 8080:8080 -p 1935:1935 -it gabekangas/owncast:latest
```


