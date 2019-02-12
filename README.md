# docker-portainer

## Get the Stack
```
curl -L https://downloads.portainer.io/portainer-agent-stack.yml -o portainer-agent-stack.yml
```

## Deploy the Stack
```
docker stack deploy --compose-file=portainer-agent-stack.yml portainer
```