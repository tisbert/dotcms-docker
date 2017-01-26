# Docker-Compose Infrastructure for dotCMS with MySQL

*You need to have docker and docker-compose installed*

It will setup 2 dotCMS instances so you can afterwards configure an environment
 with push publish support if you have en enterprise license.

## Setup

* clone this repository
* edit the `docker-compose.yml` and set volumes path to some folder your host
* run `docker-compose up -d`

This will download and start 2 dotCMS and 2 MySQL servers.

one (uat) is reachable at http://localhost:8080

the other (prod) is reachable at http://localhost:8081


## credits

Base dockerfiles taken from https://github.com/jorith88/dotcms-dockerfiles
