<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## About Project

OAuth2 server based on Laravel Passport and Laravel Breeze

## Technology Stack
- [Laravel 8](https://laravel.com/docs/8.x).
- [Laravel Passport](https://laravel.com/docs/8.x/passport).
- [Laravel Breeze](https://laravel.com/docs/8.x/starter-kits#laravel-breeze).

## Deploy

Server requirements 
- PHP ^7.4
- MySQL ^5.7
- nginx/apache

### Steps to install
- ``laravel new oauth2``
- ``composer require laravel/passport``
- ``php artisan passport:install``
- ``composer require laravel/breeze``
- ``php artisan migrate``
- ``php artisan breeze:install``
- ``npm install && npm run dev``
- ``php artisan migrate``
- ``php artisan vendor:publish --tag=passport-views``
- ``php artisan passport:client``
- ``php artisan optimize:clear``
