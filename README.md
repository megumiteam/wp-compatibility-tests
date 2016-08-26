# Compatibility Tests of WordPress and PHP

https://travis-ci.org/miya0001/wp-compatibility-tests

It runs PHPUnit tests for WordPress 3.7+ and PHP 5.3+ on the Travis CI.

## How to run tests

```
$ git clone git@github.com:miya0001/wp-compatibility-tests.git
$ bash bin/install-wp-tests.sh wordpress_test root '' localhost 4.6
$ cd tests
$ phpunit
```
