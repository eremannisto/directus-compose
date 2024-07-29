# Directus PostgresSQL Compose Template
This is a docker-compose template for Directus with PostgreSQL as database. It also includes Traefik as reverse proxy.

## Environment Variables
```env
# USER SETTINGS
ADMIN_EMAIL=<EMAIL_ADDRESS>         # Email for Directus
ADMIN_PASSWORD=<PASSWORD>           # Password for Directus

# DIRECTUS SETTINGS
DIRECTUS_VERSION=10.13.1            # Directus version
DIRECTUS_KEY=<RANDOM_KEY>           # Secret key for Directus
DIRECTUS_HASH=<RANDOM_KEY>          # Hash for Directus
DIRECTUS_DOMAIN=cms.example.com     # Domain for Directus
DIRECTUS_PORT=8055                  # Port for Directus
DIRECTUS_MAX_UPLOAD_SIZE=10mb       # Max upload size for Directus

# PostgresSQL
POSTGRES_NAME=<NAME>                # Database name for PostgresSQL
POSTGRES_USER=<NAME>                # Database name for PostgresSQL
POSTGRES_PASSWORD=<RANDOM-KEY>      # Password for PostgresSQL   

# CORS POLICY
CORS_ENABLED=true                   # Enable CORS
CORS_ORIGIN=*                       # Allowed origins
```