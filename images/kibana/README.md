# Kibana

## Deploy registry

```console
$ ./../../tools/registry/deploy-registry.sh
```

## Build image

```console
$ docker build -t 127.0.0.1:31500/kibana .
$ docker push 127.0.0.1:31500/kibana
```
