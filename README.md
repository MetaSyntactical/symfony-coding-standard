Symfony2 PHP CodeSniffer Coding Standard
========================================

A coding standard to check against the [Symfony coding standards](http://symfony.com/doc/current/contributing/code/standards.html),
copied from escapestudios/Symfony2-coding-standard which itself was copied from the -disappeared- opensky/Symfony2-coding-standard repository.

Composer integration has been additionally enabled.

Installation
------------

Require PHP_CodeSniffer and this sniff in your project `composer.json`:

```json
{
    "require-dev": {
        "squizlabs/php_codesniffer": "~2.3",
        "metasyntactical/symfony-coding-standard": "~1.0"
    }
}
``

Afterwards call CodeSniffer with the standard:

```sh
$ vendor/bin/phpcs $FILENAME --standard=vendor/metasyntactical/composer-codesniffer-hooks/Symfony2/ruleset.xml
```
