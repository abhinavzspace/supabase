# Supabase Docker

This is a minimal Docker Compose setup for self-hosting Supabase. Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get started.


# DEPLOYMENT STEPS

## updating

`docker compose restart`

## uninstalling all

```
# Stop docker and remove volumes:
docker compose down -v

# Remove Postgres data:
rm -rf volumes/db/data/
```