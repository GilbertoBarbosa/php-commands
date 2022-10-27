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

Install Breeze
```
composer require laravel/breeze --dev
php artisan breeze:install
npm install
npm run dev
php artisan migrate

```

Create mail
```
php artisan make:mail <ClassName> 

```

Create queue table
```
php artisan queue:table
php artisan migrate

```

Open interactive laravel terminal
```
php artisan tinker

```

Process queue
```
php artisan queue:listen
php artisan queue:work --tries=<number> --delay=<number>
php artisan queue:retry <id>
 
```

Create listener
```
php artisan make:listener <name>

```

Create event
```
php artisan make:event <name>

```

Storage link
```
php artisan storage:link 

```

Run Test
```
php artisan test

```

Create Test
```
php artisan make:test <testName>

```

Test with selenium
```
composer require --dev laravel/dusk

```

Show all rotes
```
php artisan route:list

```

Install sanctum
```
composer require laravel/sanctum

```
