# docker-caddy-cloudflare-proxy

The caddy-docker-proxy plugins allow for using Docker labels in place of a Caddyfile to discover and configure Caddy as new services are spun-up.
While the caddy-dns plugin from cloudflare is for allowing Caddy to access Cloudflare DNS to create self signed SSL certificates on the fly.

## Setup

Create an `.env` file by cloning `.env.example`:

```
cp .env.example .env
```

Then create a docker volume named `caddy_data`:

```
docker volume create caddy_data
```

Finally create a docker network named `caddy_network`:
```
docker network create caddy_network
```
