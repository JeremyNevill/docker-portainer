# docker-portainer

This is the simple Portainer.io setup using linux docker swarm.

The compose file is downloaded from https://downloads.portainer.io/portainer-agent-stack.yml which is referenced from https://www.portainer.io/installation/ 

## Deploy the Stack
```
docker stack deploy --compose-file=portainer-agent-stack.yml portainer
```

## Portainer UI

Browse to:

http://127.0.0.1:9000
