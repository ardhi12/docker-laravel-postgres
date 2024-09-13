## How to run:
1. Clone this repository
2. Copy .env.example to .env
3. Makesure postgres connection config is match between postgres container and .env
4. Execute command `docker compose build` to build laravel container
5. Execute command `docker compose up -d` to start all containers
6. Execute command `docker-compose exec app composer install` to install composer
5. Execute command `docker compose exec app php artisan migrate` to create add some default tables to Postgres
6. Open the webserver by http://localhost:8080/