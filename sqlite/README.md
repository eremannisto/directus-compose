# Directus SQLITE Compose Template
This is a docker-compose template for Directus with SQLITE as database. It also includes Traefik as reverse proxy.

## Environment Variables
```env
# Directus
DIRECTUS_VERSION=10.13.1                # Directus version
DIRECTUS_KEY=<RANDOM-KEY>               # Secret key for Directus
ADMIN_EMAIL=<USER-EMAIL>                # Email for Directus
ADMIN_PASSWORD=<USER-PASSWORD>          # Password for Directus

# Traefik
TRAFFIC_HASH=<RANDOM-KEY>               # Hash for Traefik
TRAFFIC_DOMAIN=example.domain.tld       # Domain for Traefik
TRAFFIC_PORT=8055                       # Port for Traefik
```



