# docker-service-metabase
run metabase using docker


# Prerequisites
need to have docker, docker-compose, postgres installed


# Start and Stop
Configure the postgres db settings in docker-compose file and run,

`make up` for starting and `make down` for stopping

Metabase runs on port 80


# Data Location
Data is stored in the postgres db given in docker-compose file.
