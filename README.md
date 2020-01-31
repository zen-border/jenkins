# Docker

CI / CD environment including Jenkins and gitbucket.

## Preresquite

Jenkins runs by default with uid = 1000. Create a jenkins directory and set the owner uid to 1000.

```bash
mkdir jenkins
chown 1000:1000 jenkins -R
```

## Get started

Start CI / CD environment.

```bash
docker-comose up -d
```

Stop CI / CD environment

```bash
docker-compose down -v
```