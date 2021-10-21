# LaravelBreezeTechTalks

Laravel Breeze
Laravel Breeze is a minimal, simple implementation of all of Laravel's authentication features, including login, registration, password reset, email verification, and password confirmation. Laravel Breeze's default view layer is made up of simple Blade templates styled with Tailwind CSS. Breeze provides a wonderful starting point for beginning a fresh Laravel application.

# Installation
First, you should create a new Laravel application, configure your database, and run your database migrations:

curl -s https://laravel.build/example-app | bash

cd example-app

php artisan migrate

 # Once you have created a new Laravel application, you may install Laravel Breeze using Composer:

composer require laravel/breeze --dev

# After Composer has installed the Laravel Breeze package, you may run the breeze:install Artisan command. This command publishes the authentication views, routes, controllers, and other resources to your application. Laravel Breeze publishes all of its code to your application so that you have full control and visibility over its features and implementation. After Breeze is installed, you should also compile your assets so that your application's CSS file is available:

php artisan breeze:install

npm install
npm run dev
php artisan migrate

Next, you may navigate to your application's /login or /register URLs in your web browser. All of Breeze's routes are defined within the routes/auth.php file.

# activate mail send

https://larainfo.com/blogs/laravel-8-email-verification-with-breeze
