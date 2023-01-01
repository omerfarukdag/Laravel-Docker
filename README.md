```
Rename .env.example to .env and update database credentials to match those in docker-compose.yml.
docker compose build
docker compose up -d
Wait for the dependencies to install, it may take a few minutes. Run without -d if you want to see progress.
docker compose exec server php artisan key:generate
docker compose exec server php artisan migrate
```