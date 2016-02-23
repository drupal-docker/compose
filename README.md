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

1. [Simple](/zaporylie/compose/tree/master/examples/simple) - MariaDB + php:apache
1. [Data containers](/zaporylie/compose/tree/master/examples/data-containers) - using Data Volume Containers
1. [Drush](/zaporylie/compose/tree/master/examples/drush) - connect drush container to your
