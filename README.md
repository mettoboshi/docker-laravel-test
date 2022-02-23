# docker-laravel-test

## usage
```
$ git@github.com:mettoboshi/docker-laravel.git
$ cd docker-laravel
$ docker compose up -d --build

$ docker compose exec app bash
$ composer install
$ cp .env.example .env
$ php artisan key:generate
$ php artisan storage:link
$ chmod -R 777 storage bootstrap/cache
$ php artisan migrate
```
