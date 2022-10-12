## About Template

This is ready admin panel template with

-   [AdminLte V3](https://adminlte.io/themes/v3/)
-   [Laravel 8](https://laravel.com/docs/8.x)
-   [Laravel-permissions (Spatie.be)](https://spatie.be/docs/laravel-permission/v3/introduction)
-   [Authorization laravel/ui](https://github.com/laravel/ui)

Laravel is accessible, powerful, and provides tools required for large, robust applications.

# Laravel 8 & AdminLte 3.0

## Setup environment

-   Clone source code from https://github.com/ngducmy393/contact_management
-   cd to root_proj_path: cp .env.example .env
-   docker-compose up -d --build
-   cd to docker/PostgreSQL && docker-compose up -d --build
-   cd to root_proj_path
-   docker exec -it contact_app /bin/bash
-   composer install
-   php artisan key:generate
-   php artisan migrate
-   chmod 777 -R /work/contact/storage
