# Setup:
### Config
edit `docker-compose.yml` to fit needs default basic auth is disabled enable and provide a email to add basic auth login

### SECRETS
 create a file `.env_encoded` in dir with docker-compose.yml, paste in any scret key in with prefix `SECRET_` ie. `SECRET_DISCORD_WEBHOOK` and ref them in flow as `{{ secret('DISCORD_WEBHOOK')}}`


#Run
have docker and docker compose installed, ensure you are in `kestra` dir and run `docker compose up -d`, to stop run `docker compose down` in same dir.

