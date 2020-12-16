```
usage: docker-compose-postgres [-h] [-c COMMAND] [-T] [--docker-compose-command DOCKER_COMPOSE_COMMAND] [-p] [-f FILE] [--env-user ENV_USER] [--env-db ENV_DB] [--service SERVICE] [-U USERNAME] [-d DBNAME]

optional arguments:
  -h, --help            show this help message and exit
  -c COMMAND, --command COMMAND
                        run only single command (SQL or internal) and exit
  -T                    disable pseudo-tty allocation. By default `docker-compose exec allocates a TTY.
  --docker-compose-command DOCKER_COMPOSE_COMMAND
                        path to docker-compose executable. Default `docker-compose`
  -p, --print           do not call subprocess. Print command only.
  -f FILE, --file FILE  specify an alternate compose file (default: docker-compose.yml)
  --env-user ENV_USER   environment variable which defines username. Default `POSTGRES_USER`
  --env-db ENV_DB       environment variable which defines dbname. Default `POSTGRES_DB`
  --service SERVICE     specify name of service. Default behaviour is to find service with image name starts with `postgres:`
  -U USERNAME, --username USERNAME
                        database user name
  -d DBNAME, --dbname DBNAME
                        database name
```