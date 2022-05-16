## MyTeamAbroad App

This app was made as part of a test for MyTeamAbroad company.

Technologies used for this project:

-   [Laravel 9](https://laravel.com/)
-   [VueJs 2](https://v2.vuejs.org/v2/guide/)
-   [InertiaJs](https://inertiajs.com/)

## Assumptions

This version of Laravel requires **PHP 8.1+**, **Composer 2** & **NodeJS 14+** for the JS dependencies.

## Installation

Here, you will find the usual instructions to install & run a typical Laravel & VueJs application.

Install composer dependencies:

```
composer install
```

Install node dependencies:

```
npm install
```

From the terminal, copy & set your environment variables with:

```
cp .env.example .env
```

In case you don't have a DB already for this project, this is a reminder to create your DB (mysql for the next example)
Now you need to open the `.env` file and set up the DB credentials with your own ones:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=place_your_db_name
DB_USERNAME=place_your_db_user_name
DB_PASSWORD=place_your_db_password
```

After setting up the credentails of the DB. Run the migrations with:

```
php artisan migrate
```

Then, create a `APP_KEY` with:

```
php artisan key:generate
```

And finally, to run the project, use:

```
php artisan serve
```
