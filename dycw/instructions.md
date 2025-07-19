https://github.com/gnzsnz/ib-gateway-docker/issues/81#issuecomment-2663889485

```bash
git clone https://github.com/gnzsnz/ib-gateway-docker.git
cd ib-gateway-docker
git switch aarch64
./update.sh latest 10.39.1b
    # see https://github.com/gnzsnz/ib-gateway-docker/pkgs/container/ib-gateway
    # last updated 2025-07-19
# update docker-compose.yml to work with latest
nano docker-compose.yml
docker compose build --pull
docker compose up
```
