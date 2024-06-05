### Configure enviroment variable
- `cp .env.example .env`

### Running Mysql in Docker-compose
- `docker-compose up -d`

### Install vendor dependencies
- `composer install`

### Migrate Database
- `php artisan make:migration <name>`
- `php artisan migrate`

### Running in local
- `php artisan serve`
