# Alpine + Node

Minimalistic *Alpine* with Node 49MB

1. publish to docker
```bash
  docker build --rm -f alpine-node/Dockerfile -t alpine-node:latest alpine-node
  docker tag alpine-node:latest evilguy/node:0.1
  docker tag alpine-node:latest evilguy/node:latest
  docker push evilguy/node:0.1
  docker push evilguy/node:latest
```