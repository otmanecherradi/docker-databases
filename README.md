# Databases Docker Compose Files

Using [Docker](https://www.docker.com/) for a global database solution

## Features

- [PostgreSQL](https://www.postgresql.org/)

  - File: [docker-compose.yml](./postgresql/docker-compose.yml)
  - Credentials
    - Username: `docker`
    - Password: `docker`
  - Management
    - [Adminer](https://www.adminer.org/) is the database manager of choice to use. Once started, use <http://localhost:8090/>

- [MysqlSQL](https://www.mysql.com/)

  - File: [docker-compose.yml](./mysql/docker-compose.yml)
  - Credentials
    - Username: `root`
    - Password: `docker`
  - Management
    - [Adminer](https://www.adminer.org/) is the database manager of choice to use. Once started, use <http://localhost:8091/>

- [MongoDB](https://www.mongodb.com/)

  - File: [docker-compose.yml](./mongodb/docker-compose.yml)
  - Credentials
    - Username: `docker`
    - Password: `docker`
  - Management
    - [mongo-express](https://github.com/mongo-express/mongo-express) is the database manager of choice to use. Once started, use <http://localhost:8092/>

- [Oracle Express Edition](https://www.oracle.com/in/database/technologies/appdev/xe.html)

  - File: [docker-compose.yml](./oracle-ex/docker-compose.yml)
  - Credentials
    - Username: `docker`
    - Password: `docker`
  - Management
    - Built in

- [Cassandra](https://cassandra.apache.org/_/index.html)

  - File: [docker-compose.yml](./cassandra/docker-compose.yml)
  - Credentials
    - Username: `docker`
    - Password: `docker`
  - Management
    - -
