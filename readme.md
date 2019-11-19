<h2>INSTALLATION</h2>
<ol>
    <li>Clone to your server</li>
    <li>Run `composer install` to install all the dependencies</li>
<li>Create `.env` in application root cp .env.example .env set up your db name.set username to root and no password</li>
<li>Run `php artisan key:generate` to generate application key</li>
<li>Run `php artisan migrate` to migrate tables to your database.</li>
<li> run `php artisan serve` to start server and app should be ready.</li>
    </ol>
