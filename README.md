# Aplicacion de ejemplo para curso de Docker, del canal Hola Mundo.

Curso completo gratis aca: https://www.youtube.com/watch?v=4Dko5W96WHg

Para setear mongo container 

```

docker create -p27017:27017 --name monguito -e MONGO_INITDB_USERNAME=nico -e MONGO_INITDB_ROOT_PASSWORD=password mongo

```

# review info here
https://hub.docker.com/_/mongo