# create envfile  .env

```bash
MONGO_ROOT_USER=devroot
MONGO_ROOT_PASSWORD=devroot
MONGOEXPRESS_LOGIN=dev
MONGOEXPRESS_PASSWORD=dev
```

# stop docker container as restart: always

```
$ docker update --restart=no <ContainerId>

$ docker-compose down
```
