# Hello World
Выводит фразу "Hello From Composer Package"
## Требования
- PHP >= 7.0
## Установка
```bash
composer require amikha1lov/otus-composer-package
```
## Использование
```php
$helloWorld = new HelloWorld();
echo $helloWorld->sayHelloFromComposerPackage();
```