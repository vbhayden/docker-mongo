## Dockerized MongoDB

Basic Docker setup to keep me from having to install MongoDB directly onto a machine.

## TL;DR
Get the codebase and install dependencies:
```bash
git clone https://github.com/vbhayden/docker-mongo
cd docker-mongo
sudo ./install-reqs.sh
```
Configure your Mongo instance by copying the example environment file and adding your own values:
```
cp example.env .env
```

Stand it up:
```
sudo docker-compose up -d --build
```
