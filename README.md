# Course Platform

This is a a project being built with Laravel 8 and NuxtJS, for Educational purposes.
I will continue to work on this when I can, but feel free to fork it and build upon it.

## Getting Started

To get started please ensure you have the following installed:

- Composer
- NPM and NodeJS
- PHP 7.2.5 or newer.

# Installing

## Backend

In order to install it please clone the repo. Then in the backend directory run these commands and ensure to have set up database configuration in .env file:

```
composer install
php artisan migrate
```

To run the backend code please use Laravel's in-built `php artisan serve` function to run it locally.

### .env File

Please ensure that you copy .env.example and configure the database and email settings to your preference. Additionally, you should add `SESSION_DOMAIN=localhost` for local hosting and change it to your backend domain name when published.

## Frontend

In order to setup the frontend code please install the dependinces using `npm install`. To run the frontend please use `npm run dev`

### Built With

- [Laravel 8](https://laravel.com/docs/8.x) - backend framework.
- [NuxtJS](http://nuxtjs.org/) - frontend framework.

### License

This project is licensed under the MIT license - see the [LICENSE.MD](https://github.com/Matildevoldsen/course-platform/blob/master/LICENSE.md) for details.
