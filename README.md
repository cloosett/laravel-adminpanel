git clone https://github.com/cloosett/laravel-adminpanel
cd laravel-adminka
cp .env.example .env
composer install
php artisan key:generate
php artisan serve
Create a database

mysql
create database laravelblog;
exit;
php artisan migrate

adminka:
