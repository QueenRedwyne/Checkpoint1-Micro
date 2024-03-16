### Comando "docker" para executar a aplicação a partir do docker hub com profile "dev"

```
docker run -d -p 8080:8080 -e PROFILE=dev annerezende/fiap-checkpoint1
```

### Comando "docker" para executar a aplicação a partir do docker hub com profile "stg"

```
docker run -d -p 8080:8080 -e PROFILE=stg annerezende/fiap-checkpoint1
```

### Comando "docker" para executar a aplicação a partir do docker hub com profile "prd"

```
docker run -d -p 8080:8080 -e PROFILE=prd annerezende/fiap-checkpoint1
```
