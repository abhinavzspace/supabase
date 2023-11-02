# Supabase Docker

This is a minimal Docker Compose setup for self-hosting Supabase. Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get started.


# DEPLOYMENT STEPS

- paste secret keys from minio to .env local.
- `touch .env` on server.
- copy content from local .env to .env prod.
- paste LOGFLARE_API_KEY in .env and ./volumes/logs/vector.yml