INSTALLATION
1.Clone to your server
2.Run `composer install` to install all the dependencies
3.Create `.env` in application root cp .env.example .env set up your db name.set username to root and no password
4.Run `php artisan key:generate` to generate application key
5.Run `php artisan migrate` to migrate tables to your database.
6. run `php artisan serve` to start server and app should be ready.
