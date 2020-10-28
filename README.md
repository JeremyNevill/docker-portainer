# docker-portainer

This is the default Portainer.io setup using linux docker swarm... 

The compose file is downloaded from https://downloads.portainer.io/portainer-agent-stack.yml 

## Deploy the Stack
```
docker stack deploy --compose-file=portainer-agent-stack.yml portainer
```

## Portainer UI

http://127.0.0.1:9000
