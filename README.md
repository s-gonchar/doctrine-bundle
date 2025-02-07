# Doctrine Bundle Project
### Doctrine Bundle Project - Symfony 4+

___Version 1.0.10___

## Features
* [Add a prefix to all tables within a connection.](docs/TablePrefix.md)

## Installation
#### Applications that use Symfony Flex
Open a command console, enter your project directory and execute:

```$ composer require crayner/doctrine-bundle```

#### Applications that don't use Symfony Flex
__Step 1: Download the Bundle__

Enter your project directory and execute the following command to download the latest stable version of this bundle:

```$ composer require crayner/doctrine-bundle```

_This command requires you to have Composer installed globally, as explained in the installation chapter of the Composer documentation._

__Step 2: Enable the Bundle__

Then, enable the bundle by adding it to the list of registered bundles in the config/Bundles.php file of your project:
```php
<?php
return [
    //...
    //
    Crayner\Doctrine\CraynerDoctrineBundle::class => ['all' => true],
];
```
__To Do (Limitations)__
* The prefix is not yet effective when using the migration bundle.

[MIT License](LICENSE.md)