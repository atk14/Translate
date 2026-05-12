Translate
=========

[![Tests](https://github.com/atk14/Translate/actions/workflows/tests.yml/badge.svg?branch=master)](https://github.com/atk14/Translate/actions/workflows/tests.yml)

A PHP class for converting strings between character maps

Basic usage
-----------

    echo Translate::Trans($utf8_content,"UTF-8","ISO-8859-2");

Installation
------------

Use the Composer to install the panel.

    cd path/to/your/project/
    composer require atk14/translate dev-master

Testing
-------

Translate is tested automatically via GitHub Actions across PHP 5.6 to PHP 8.5.

Tests use the [atk14/tester](https://packagist.org/packages/atk14/tester) wrapper for [phpunit/phpunit](https://packagist.org/packages/phpunit/phpunit).

Install development dependencies:

```bash
composer update --dev
```

Run the test suite:

```bash
./vendor/bin/run_unit_tests test
```

Licence
-------

Translate is free software distributed [under the terms of the MIT license](http://www.opensource.org/licenses/mit-license)
