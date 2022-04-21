# Códigos Laravel

[Migrations](https://laravel.com/docs/9.x/migrations)

Migrate
php artisan serve

php artisan migrate

php artisan make:controller Nome_Controller
php artisan make:model Nome_Model
php artisan make:seed CreateUserAndAddressSeed
phpartisan db::seed

php artisan make:migration alter_products_table

php artisan make:migration add_category_to_products_table
php artisan make:migration create_flights_table

php artisan migrate:status
php artisan migrate:reset
php artisan migrate:fresh
php artisan migrate:refresh
php artisan migrate:refresh --seed
php artisan migrate:refresh --step=5
php artisan migrate --force

php artisan migrate:rollback
php artisan migrate:rollback --step=5

