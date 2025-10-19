# KUB Infrastructure

This repository contains files for local and service deployment.

---

## Local Setup

**Prerequisites:**

- Docker installed ([Install Docker](https://docs.docker.com/engine/install/))
- Docker Compose installed ([Install Docker Compose](https://docs.docker.com/compose/install/))

**Start the infrastructure:**

```sh
docker compose up -d
```

**Check running containers:**

```sh
docker ps
```

**Stop the services:**

```sh
docker compose down
```

**To run backend container, copy configuration file and modify if needed:**

```shell
cp config/secrets.properties.example config/secrets.properties
```
