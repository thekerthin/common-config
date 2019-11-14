# common-config

## Getting Started

Down below you have a list of steps that help you to start all need services.

### Start infrastructure services

Turn on services
```sh
$ docker-compose up postgresql rabbitmq
```

Turn off services
```sh
$ docker-compose down
```

### Clone utilities

[utilities / miscellaneous](https://github.com/thekerthin/kerthin-miscellaneous.git)

### Clone services

[user service](https://github.com/thekerthin/user-service)

[blog service](https://github.com/thekerthin/blog-service)


## Extras

Go in a container
```sh
$ docker exec -u root -it <container id> bash
```

Go in a container
```sh
$ docker exec -u root -it <container id> bash
```

Exec PSQL queries
```sh
$ psql -U <psql server user name> -d <database name> -c "<SQL QUERY>"
```
