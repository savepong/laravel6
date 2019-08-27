# Laravel 6

## Testing

Running Tests

```bash
vendor/bin/phpunit
```

## Queues

Running Queues worker

```bash
php artisan queue:work
php artisan queue:work --tries=3
```

Check for failed queues

```bash
php artisan queue:failed
```

Retry queue

```bash
php artisan queue:retry [ID]
php artisan queue:work
```

## Reference

-   Testing: https://medium.com/@DCzajkowski/testing-laravel-authentication-flow-573ea0a96318
-   Queues: https://voltagead.com/the-basics-of-laravel-queues-using-redis-and-horizon/
