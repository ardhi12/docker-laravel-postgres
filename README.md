## How to run:
1. Clone this repository
2. Makesure postgres connection config is match between docker-compose.yaml and .env
3. Execute command `docker compose build` to build laravel container
4. Execute command `docker compose up -d` to start all containers
5. Execute command `docker compose exec app php artisan migrate` to create add some default tables to Postgres
6. Open the webserver by http://localhost:8081/