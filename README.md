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
- ``composer require laravel/breeze``
- ``php artisan migrate``
- ``php artisan passport:install``
- ``php artisan breeze:install``
- ``npm install && npm run dev``
- ``php artisan vendor:publish --tag=passport-views``
- ``php artisan passport:client``
- ``php artisan optimize:clear``

Config according to official documentation.
>NOTE: For the correct display of styles, add a link to the bootstrap styles in the resources/vendor/passport/authorize.blade.php file
``<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">``

