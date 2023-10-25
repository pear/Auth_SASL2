# Auth_SASL2 - Abstraction of various SASL2 mechanism responses

[![Build Status](https://travis-ci.org/pear/Auth_SASL2.svg?branch=master)](https://travis-ci.org/pear/Auth_SASL2)
    

Provides code to generate responses to common SASL2 mechanisms, including:
- Anonymous
- Cram-MD5 (DEPRECATED)
- Digest-MD5 (DEPRECATED)
- External
- Login (Pseudo mechanism) (DEPRECATED)
- Plain
- SCRAM

[Homepage](http://pear.php.net/package/Auth_SASL2/)


## Installation
For a PEAR installation that downloads from the PEAR channel:

`$ pear install pear/auth_sasl2`

For a PEAR installation from a previously downloaded tarball:

`$ pear install Auth_SASL2-*.tgz`

For a PEAR installation from a code clone:

`$ pear install package.xml`

For a local composer installation:

`$ composer install`

To add as a dependency to your composer-managed application:

`$composer require pear/auth_sasl2`


## Tests
Run  the tests from a local composer installation:

`$ ./vendor/bin/phpunit`


## License
BSD-3-Clause license
