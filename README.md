PHPUnit Coverage Listener
=========================
[![Build Status](https://travis-ci.org/php-loep/phpunit-coverage-listener.png)](https://travis-ci.org/php-loep/phpunit-coverage-listener) [![Coverage Status](https://coveralls.io/repos/php-loep/phpunit-coverage-listener/badge.png?branch=master)](https://coveralls.io/r/php-loep/phpunit-coverage-listener?branch=master)

PHPUnit Coverage Listener is a utility library that allow you to process the PHPUnit code-coverage information and send it into some remote location via cURL. It could be used, for example, to send the payload data for [Coveralls](https://coveralls.io/) effortless from your composer-based project.

Install
-------

Via Composer

    {
        "require": {
            "league/phpunit-coverage-listener": "~1.0"
        }
    }
    
Requirement
-----------

* PHP >= 5.3.3
* PHPUnit
* xDebug (inherit from PHPUnit Code-Coverage requirement)

Usage
-----

Changelog
---------

Contributing
------------

Support
-------


License
-------

PHPUnit Coverage Listener is released under the MIT License. See the bundled
[LICENSE](https://github.com/php-loep/phpunit-coverage-listener/blob/master/LICENSE) file for details.