# moodle-docker

## Install Docker Engine and Docker Compose

https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository

## Clone this repo

```bash
git clone https://github.com/taylorjadin/moodle-docker
```

make sure to edit db passwords in `docker-compose.yml`

## run it and tail the logs

```bash
docker-compose up -d && docker-compose logs -f
```
