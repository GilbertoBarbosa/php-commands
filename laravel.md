# php-laravel-commands

List commands
```
php artisan list

```

Create project
```
composer create-project laravel/laravel <projectname>

```

Run Server
```
php artisan serve --host=<host> --port=<port>

```

Create controller
```
php artisan make:controller <controllername> --resource

```

Make Component
```
php artisan make:component <componentname>

```

Make Request
```
php artisan make:request <requestname>

```

Make Model with migration
```
php artisan make:model <modelname> -m

```

Make Migration
```
php artisan migrate

```

Remove all tables and do migration again
```
php artisan migrate:fresh

```

Install debugbar
```
php composer require barryvdh/laravel-debugbar --dev 

```

Create provider
```
php artisan make:provider <ProviderName> 

```

Create middleware
```
php artisan make:middleware <MiddlewareName> 

```

