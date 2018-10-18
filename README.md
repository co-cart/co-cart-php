# CoCart API - PHP Client

> In development. Nothing here yet.

A PHP wrapper for CoCart. Easily interact with CoCart using this library.

## Installation

```
composer require co-cart/co-cart
```

## Setup

Setup for CoCart requires WooCommerce 3.0 or later.

```php
require __DIR__ . '/vendor/autoload.php';

use CoCart\Client;

$cocart = new CoCart_Client(
    'http://example.com',
    [
        'version' => 'cocart/v1',
    ]
);
``
