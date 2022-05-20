## laravel + Vue js dashboard
mini Project in Laravel and vue js. Real World Laravel 8x + vue js Dashboard.Task management and project management system. Dashboard features such as: Complete Dashboard, Custom Authentication, Email Verification, custom-login-register-forgot password (without jetstream).

## How to use
1. git clone the project using git clone command...
2. Copy `.env.example file to .env`
3. Edit database credentials in .env file
4. Run `composer install`
5. Run `npm install`
6. Run `php artisan key:generate`
7. Run `php artisan migrate`
8. for  `mail` follow this
```
MAIL_MAILER=
MAIL_HOST=
MAIL_PORT=
MAIL_USERNAME=      #Your Email ID #
MAIL_PASSWORD=      #Your Email Password #
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS=  #Your Email ID #
MAIL_FROM_NAME="${APP_NAME}"
```
9. Run `npm run dev`
10. Run `php artisan serve` 
11. `http://localhost:8000/`

