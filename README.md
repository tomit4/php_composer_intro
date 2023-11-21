## PHP Composer Intro

Just learning how to install PHP composer and start a project with it.

Just install composer using your native package manager, don't bother with the
official docs for now.

```
sudo pacman -S composer
```

Otherwise take a look at the [Official Docs On Basic Usage](https://getcomposer.org/doc/01-basic-usage.md).

The very very basics of starting with composer is simply to follow the
instructions careful during the cli prompt when you initialize a project using
composer:

```
composer init
```

You'll want to explore the php world's version of npm, [Packagist](https://packagist.org/).

Make sure to add the vendor directory to your .gitignore, (can be thought of as alike to node_modules).

In order to very basically serve php, you can utilize the -S flag to set up a
basic server:

```
php -S localhost:8000
```

By default looks for index.php in pwd, you can also specify a file:

```
php -S localhost:8000 hello.php
```
