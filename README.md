# Trial-Slim

## Slim Framework 3 Skeleton Application

Use this skeleton application to quickly setup and start working on a new Slim Framework 3 application. This application uses the latest Slim 3 with the PHP-View template renderer. It also uses the Monolog logger.

This skeleton application was built for Composer. This makes setting up a new Slim Framework application quick and easy.

### Install the Application

Run this command from the directory in which you want to install your new Slim Framework application.

    php composer.phar create-project slim/slim-skeleton [my-app-name]

Replace `[my-app-name]` with the desired directory name for your new application. You'll want to:

* Point your virtual host document root to your new application's `public/` directory.
* Ensure `logs/` is web writeable.

### Configure Database

You can use a database ORM such as [Eloquent](https://laravel.com/docs/5.1/eloquent) to connect your SlimPHP application to a database.

Run this command to install Eloquent to the application.

    composer require illuminate/database "~5.1"

That's it! Now go build something cool.
