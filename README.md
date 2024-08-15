# Hello World
Выводит фразу "Hello From Composer Package"
## Требования
- PHP >= 8.1
## Установка
```bash
composer require amikha1lov/otus-composer-package
```
## Использование
```php
$helloWorld = new HelloWorld();
echo $helloWorld->sayHelloFromComposerPackage();
```