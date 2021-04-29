## Who Paid 99¢ Clone with Slim

Demo Project of Who Paid 99¢ Clone with Slim

### Controllers

- [HomeController](https://github.com/akr4m/Who-Paid-99-Clone-with-Slim/blob/main/app/Controllers/HomeController.php)
- [PaymentIndexController](https://github.com/akr4m/Who-Paid-99-Clone-with-Slim/blob/main/app/Controllers/PaymentIndexController.php)
- [PaymentStoreController](https://github.com/akr4m/Who-Paid-99-Clone-with-Slim/blob/main/app/Controllers/PaymentStoreController.php)

### Web Routes

```php
<?php

use App\Controllers\HomeController;
use App\Controllers\PaymentIndexController;
use App\Controllers\PaymentStoreController;

$app->get('/', HomeController::class);

$app->post('/payments', PaymentStoreController::class);
$app->get('/payments', PaymentIndexController::class);
```
