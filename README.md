# Calculator Class

The `Mereo` class is a simple PHP class that provides basic arithmetic operations: addition, subtraction, and multiplication.

## Installation

You can include the `Mereo` class in your PHP project by simply running the command below:
```shell
composer require mereo-desenvolvimento/php-mereo
```
## Usage

To use the `Calculator` class, you need to instantiate the class and then call its methods to perform arithmetic operations.

### Example

```php
<?php

require __DIR__.'/vendor/autoload.php';

use MereoDesenvolvimento\PHPMereo\Mereo;

$calculator = new Mereo();

$sum = $calculator->add(2, 3);
echo "Sum: " . $sum;

$difference = $calculator->subtract(5, 3);
echo "Difference: " . $difference;

$product = $calculator->multiply(4, 3);
echo "Product: " . $product;
