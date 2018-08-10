# [symfony-flex-init](https://symfony-flex-init.github.io)/website-skeleton
Composer init script to simulate  symfony/website-skeleton based on symfony/skeleton

[![Build Status](https://travis-ci.org/symfony-flex-init/website-skeleton.svg?branch=master)](https://travis-ci.org/symfony-flex-init/website-skeleton)

## Tested with...
### PHP 7.2, 7.1
* Symphony 4.1
* symfony/skeleton (v4.1.3.2)
* symfony/website-skeleton (v4.1.3.3)

### Symfony 4.0
* Untested!

### PHP 7.0
* Symfony 3.4
* symfony/skeleton (v3.4.14.3)
* symfony/website-skeleton (v3.4.14.4)

## Differences between symfony/skeleton and symfony/website-skeleton
### ctype
* symfony/skeleton requires ext-ctype: * and replaces symfony/polyfill-ctype: *.
* symfony/website-skeleton (4.1.3.3) ignores ctypes.

## Some installed packages are not up to date (composer feature ?)
* With symfony/website-skeleton (4.1.3.3) and php 7.2, ocramius/proxy-manager needs to be updated!
* An slightly outdated composer.lock file seems to be downloaded!
