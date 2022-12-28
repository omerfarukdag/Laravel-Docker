```
docker-compose build
docker-compose up -d
docker-compose exec server composer install
docker-compose exec server php artisan key:generate
docker-compose exec server php artisan migrate
```