web: composer install --optimize-autoloader --no-dev && php artisan migrate --force && php artisan storage:link && chmod -R 777 storage bootstrap/cache && php artisan config:cache && php artisan route:cache && vendor/bin/heroku-php-apache2 -F fpm_custom.conf public/