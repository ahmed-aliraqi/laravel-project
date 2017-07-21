Laravel Scaffolding
=====================
A non-official laravel application scaffolding that includes `debugbar`, `ide-helper` and `.php_cs` configurations.
Mirrored from [https://github.com/laravel/laravel.git](https://github.com/laravel/laravel.git).

## Requirements
The requirements is the same as of the [official requirements](https://laravel.com/docs/5.4/installation#server-requirements) plus the following requirements needs to be in the developer's machine.

* [PHP Coding Standards Fixer](http://cs.sensiolabs.org/#globally-composer) >= 2.3.2
* NPM >= 5.0.0
* Node >= 7.0.0

## Installation
You can also install Laravel via Composer by issuing the `create-project` command in your terminal:
```
composer create-project --prefer-dist alshahawi/laravel:dev-scaffolding/5.4 blog
```
The above command will install a new laravel 5.4 application for you.

## Composer Scripts
We added composer scripts to avoid long and repeated commands. These scripts are:
```
composer php-cs:issues # Used for checking for any configured code style issues.

composer php-cs:fix # Used for fix any configured code style issues automatically.

composer auto-complete:generate # Used for generating ide helper files.

composer php-cs:fix # Used for clear application cache files.
```
