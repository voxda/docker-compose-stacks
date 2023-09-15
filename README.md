Docker Compose Stacks used within the voxda.io tutorials
---

## Overview
This repo contains docker compose stacks for popular tools within the devops community.  As voxda.io adds new articles as part of its "DevOps Sucks" series new stacks will be added.  

## What is docker compose?

Docker compose is a tool for defining and running multi-container Docker applications with a single command.  Its great for DevOps local development due to the amount of tools that have to run together.  

Learn more at Docker.com Docs: [Compose Docs](https://docs.docker.com/compose/)  

## How to use?

Clone this repository and run the docker compose file inside the directory.

Example:

Inside directory e.g. `sonarqube`

```
sonarqube $> docker-compose up
```

use `-d` to start compose in detach mode

## Stacks

| Stack                            | Standalone | Cluster |
|----------------------------------|------------|---------|
| Prometheus + Grafana             | ✅          |         |
| Prometheus Push Gateway          | ✅          |         |
| Jaeger                           | ✅          |         |
| SonarQube                        | ✅          |         |
| Apache Kafka                     | ✅          | ✅       |
| Debezium - Postgres              | ✅          |         |
| Debezium - MySQL                 | ✅          |         |
| Postgres                         | ✅          | ✅       |

## How to contribute

Raise a pull request for new devops tools or improvements to the current stacks.  

## Credit
This repo was forked from [ninadingole/docker-compose-stacks](https://github.com/ninadingole/docker-compose-stacks). Check out their repo for other credit stacks.