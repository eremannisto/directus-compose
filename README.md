# Directus Compose Template
This is a template for creating a new Directus project using Docker Compose. You can choose between a PostgreSQL or SQLite database. It also uses a Redis cache for improved performance, which is emptied during each deployment. It also makes a presistent volume for the database to keep the data between deployments.

## Usage
Docker run command for PostgreSQL:
```bash
(docker compose -p <container-id> -f ./postgres/docker-compose.yml up -d --build --remove-orphans)
```

Docker run command for SQLite:
```bash
(docker compose -p <container-id> -f ./sqlite/docker-compose.yml up -d --build --remove-orphans)
```

Check environment variables in the `/posgres` or `/sqlite` folder to see the default values.