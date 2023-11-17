# docker compose snippets

## Contents
1. [docker-compose-postgres-pgadmin](#docker-compose-postgres-pgadmin)
2. [Something else](#something-else)

### <a id="docker-compose-postgres-pgadmin"></a> Run docker-compose-postgres-pgadmin.yml

### Start
```
docker compose -f docker-compose-postgres-pgadmin.yml up -d
```
or rename file to: **docker-compose.yml**

```
docker compose up -d
```
### Stop
```
docker compose -f docker-compose-postgres-pgadmin.yml down
```
or if file is called: **docker-compose.yml**

```
docker compose down
```
#### View running containers in Docker Desktop
![PGAdmin & postgres container in Docker Desktop](./images/01_pgadmin_postgres_docker.png)

#### Enter the master password for PGAdmin
![Enter the master password for PGAdmin](./images/02_pgadmin_master_password.png)

#### Add new server
![Add new server](./images/03_pgadmin_add_new_server.png)

#### Set new server name
![Set new server name](./images/04_pgadmin_set_new_server_name.png)

#### Connect to postgres running in docker container
![Connect to postgres running in docker container](./images/05_connect_to_postgres_database_in_container.png)

#### Connected
![Connected](./images/06_connected.png)

---

### <a id="something-else"></a> Something else