# docker-circleci-node

### Build & push to docker hub

```sh
docker build .
docker login
docker images
docker tag <IMAGE ID> agreg0ire/circleci-node:first
docker push agreg0ire/circleci-node
```
