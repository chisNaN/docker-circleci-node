# docker-circleci-node

>An official circle-ci node image including `aws-cli` installed with `PIP` for `s3` deploy

### Process to build & push to docker hub

```sh
docker build .
docker login
docker images
docker tag <IMAGE ID> agreg0ire/circleci-node:latest
docker push agreg0ire/circleci-node
```
