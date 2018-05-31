# Kong API Gateway example docker stack

## Requirements

- Docker with swarm mode enabled

## Deploy

Make sure your docker server is part of a swarm by running

- `docker swarm init`

Deploy the stack defined in docker-compose.yml

- `docker stack deploy -c docker-compose.yml kong`
