# Примитивный калькулятор

Калькулятор, позволяющитй сложить два числа.

## Требования

- PHP 7.4

## Установка

```bash
$ composer require myklon/simple-package
```

## Использование

```php
<?php
$calculator = new Calculator();
echo $calculator->sum(1, 2); // 3
```