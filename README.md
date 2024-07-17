# docker-caddy-cloudflare-proxy

The caddy-docker-proxy plugins allow for using Docker labels in place of a Caddyfile to discover and configure Caddy as new services are spun-up.
While the caddy-dns plugin from cloudflare is for allowing Caddy to access Cloudflare DNS to create self signed SSL certificates on the fly.

## Setup

All that's required for setup is to copy or rename `.env.example` to `.env`

```
cp .env.example .env
```
