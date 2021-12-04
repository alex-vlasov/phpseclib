# phpseclib - PHP Secure Communications Library

[![Build Status](https://travis-ci.com/phpseclib/phpseclib.svg?branch=master)](https://travis-ci.com/github/phpseclib/phpseclib)

## Supporting phpseclib

- [Become a backer or sponsor on Patreon](https://www.patreon.com/phpseclib)
- [One-time donation via PayPal or crypto-currencies](http://sourceforge.net/donate/index.php?group_id=198487)
- [Subscribe to Tidelift](https://tidelift.com/subscription/pkg/packagist-phpseclib-phpseclib?utm_source=packagist-phpseclib-phpseclib&utm_medium=referral&utm_campaign=readme)

## Introduction

MIT-licensed pure-PHP implementations of the following:

SSH-2, SFTP, X.509, an arbitrary-precision integer arithmetic library, Ed25519 / Ed449 / Curve25519 / Curve449, ECDSA / ECDH (with support for 66 curves), RSA (PKCS#1 v2.2 compliant), DSA / DH, DES / 3DES / RC4 / Rijndael / AES / Blowfish / Twofish / Salsa20 / ChaCha20, GCM / Poly1305

* [Browse Git](https://github.com/phpseclib/phpseclib)

## Documentation

* [Documentation / Manual](https://phpseclib.com/)
* [API Documentation](https://api.phpseclib.com/master/) (generated by Doctum)

## Branches

### master

* Development Branch
* Unstable API
* Do not use in production

### 3.0

* Long term support (LTS) release
* Major expansion of cryptographic primitives
* Minimum PHP version: 5.6.1
* PSR-4 autoloading with namespace rooted at `\phpseclib3`
* Install via Composer: `composer require phpseclib/phpseclib:~3.0`

### 2.0

* Long term support (LTS) release
* Modernized version of 1.0
* Minimum PHP version: 5.3.3
* PSR-4 autoloading with namespace rooted at `\phpseclib`
* Install via Composer: `composer require phpseclib/phpseclib:~2.0`

### 1.0

* Long term support (LTS) release
* PHP4 compatible
* Composer compatible (PSR-0 autoloading)
* Install using Composer: `composer require phpseclib/phpseclib:~1.0`
* Install using PEAR: See [phpseclib PEAR Channel Documentation](http://phpseclib.sourceforge.net/pear.htm)
* [Download 1.0.19 as ZIP](http://sourceforge.net/projects/phpseclib/files/phpseclib1.0.19.zip/download)

## Security contact information

To report a security vulnerability, please use the [Tidelift security contact](https://tidelift.com/security). Tidelift will coordinate the fix and disclosure.

## Support

Need Support?

* [Checkout Questions and Answers on Stack Overflow](http://stackoverflow.com/questions/tagged/phpseclib)
* [Create a Support Ticket on GitHub](https://github.com/phpseclib/phpseclib/issues/new)
* [Browse the Support Forum](http://www.frostjedi.com/phpbb/viewforum.php?f=46) (no longer in use)

## Special Thanks

Special Thanks to our Patreon sponsors!:

- Allan Simon

## Contributing

1. Fork the Project

2. Ensure you have Composer installed (see [Composer Download Instructions](https://getcomposer.org/download/))

3. Install Development Dependencies

    ``` sh
    composer install
    ```

4. Create a Feature Branch

5. (Recommended) Run the Test Suite

    ``` sh
    vendor/bin/phpunit
    ```
6. (Recommended) Check whether your code conforms to our Coding Standards by running

    ``` sh
    vendor/bin/phing -f build/build.xml sniff
    ```

7. Send us a Pull Request
