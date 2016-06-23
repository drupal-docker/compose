docker-compose FTW!
=============

Orchestrate containers with drupal-compose.

# Description

Sometimes setting up environment can take a while even if we're using Docker.
Docker has nice tool which helps you manage your multi-container application -
docker-compose. docker-compose is a small command-line tool which reads
configuration stored in YAML file (docker-compose.yml) and builds your
application based on it. You can download it from
[docker.com](https://docs.docker.com/compose/install/)

In this repository you'll find a few examples how to start orchestrate your
multi-container app with docker-compose.

Available examples:

1. [Simple](/examples/01-simple) - MariaDB + php:apache
1. [Data containers](/examples/02-data-containers) - Data Volume Containers
1. [Drush](/examples/03-drush) - run drush container on demand
