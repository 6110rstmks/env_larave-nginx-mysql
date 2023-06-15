Reference site: https://www.cloudsigma.com/deploying-laravel-nginx-and-mysql-with-docker-compose/

## step

git clone https://github.com/laravel/laravel.git laravel-web

cd laravel-web

docker run --rm -v $(pwd):/app composer install

sudo chown -R $USER:$USER laravel-web

==========================

do `php artisan migrate` in app container.

