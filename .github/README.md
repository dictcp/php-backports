# php-backports

This is the drop-in replacement Docker image with security backports for PHP 7.x

It builds docker image with [docker/php](https://hub.docker.com/_/php) toolchain and security patches from [remicollet/php-src-security](https://github.com/remicollet/php-src-security).

```
$ docker run ghcr.io/dictcp/php-backports:7.2.34-cli-bullseye php --version
PHP 7.2.34 (cli) (built: Jun 28 2024 02:27:54) ( NTS )
Copyright (c) 1997-2018 The PHP Group
Zend Engine v3.2.0, Copyright (c) 1998-2018 Zend Technologies
```

## Available Tags

- 7.0: `7.0.33-apache-bullseye`, `7.0.33-cli-bullseye`, `7.0.33-fpm-bullseye`, `7.0.33-zts-bullseye`
- 7.2: `7.2.34-apache-bullseye`, `7.2.34-cli-bullseye`, `7.2.34-fpm-bullseye`, `7.2.34-zts-bullseye`
- 7.4: `7.4.33-apache-bullseye`, `7.4.33-cli-bullseye`, `7.4.33-fpm-bullseye`, `7.4.33-zts-bullseye`

## Other LTS / backports attempts for EOL-ed PHP versions

### OSS Community
- https://github.com/remicollet/php-src-security
- https://github.com/shivammathur/php-src-backports
- https://github.com/centminmod/centminmod/tree/master/patches/php
- https://github.com/zboszor/meta-parallel-php/tree/main/recipes-php/php

### Distribution
- Ubuntu
	- PHP 7.2 in Ubuntu 1804 LTS
	- PHP 7.4 in Ubuntu 2004 LTS
	- PHP 8.1 in Ubuntu 2204 LTS
- RHEL
	- PHP 7.3 in RHEL 7, until 2024
	- PHP 7.4 in RHEL 8, until 2029
	- PHP 8.0 in RHEL 9, until 2032

### Commenical support
- https://www.zend.com/services/php-long-term-support
- https://www.cloudlinux.com/features/#hardened-php
- https://www.freexian.com/lts/php/
