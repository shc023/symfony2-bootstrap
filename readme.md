# Symfony Bootstrap

Symfony Bootstrap is a base [symfony 2.1](http://symfony.com/) package that is setup to create new applications quickly. From here on we'll assume you know what you're doing.

## Beta Disclaimer

Symfony 2.1 and most of the dependent projects are in beta / RC status right now. When 2.1 and these depedencies are released the `composer.json` file will be updated to reflect version branches rather than `dev-master`. For now, be forwarned that the packages aren't stable.

## Includes

- (+) Default symfony 2.1 goodies
- (-) Acme Demo bundle
- (+) MongoDB

## Things I'd Like to Add

- (+) Twitter Bootstrap
- (+) SASS
- (+) Cache

## Install

Remove `composer.lock` from `.gitignore`. You should use the one created after you run `composer install` (below).

Using [composer](http://getcomposer.org/)'s global install:

	$ git://github.com/cbednarski/symfony2-bootstrap.git
	$ composer install

Execute the `check.php` script from the command line:

	$ php app/check.php

Access the `config.php` script from a browser:

	http://localhost/path/to/symfony/app/web/config.php

