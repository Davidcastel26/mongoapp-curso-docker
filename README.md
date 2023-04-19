# Aplicacion de ejemplo para curso de Docker, del canal Hola Mundo.

Curso completo gratis aca: https://www.youtube.com/watch?v=4Dko5W96WHg

Para setear mongo container 

```

docker create -p27017:27017 --name monguito -e MONGO_INITDB_USERNAME=nico -e MONGO_INITDB_ROOT_PASSWORD=password mongo

```

# review info here
https://hub.docker.com/_/mongo

crear un contenedor dentro de una envoriment de red

```
docker create -p27017:27017 --name monguito --network mired -e MONGO_INITDB_ROOT_USERNAME=nico -e MONGO_INITDB_ROOT_PASSWORD=password mongo
```

create an image
```
docker create -p3000:3000 --name chanchito --network mired miapp:1
```

Please review the file docker-compose.ylm
There we build the compose in order to work with everything


```
Control + C
```

stop the services

# docker compose down
this commant will remove the containers ralested with the docker compose
