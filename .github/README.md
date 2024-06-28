# dictcp/php-backports

This is the drop-in replacement Docker image with security backports for PHP 7.x

It builds docker image with docker/php toolchain and security patches from [remicollet/php-src-security](https://github.com/remicollet/php-src-security).

```
$ docker run ghcr.io/dictcp/php-backports:7.2.34-cli-bullseye php --version
PHP 7.2.34 (cli) (built: Jun 28 2024 02:27:54) ( NTS )
Copyright (c) 1997-2018 The PHP Group
Zend Engine v3.2.0, Copyright (c) 1998-2018 Zend Technologies
```

## Other backports attempt for EOL-ed PHP

OSS
- https://github.com/remicollet/php-src-security
- https://github.com/shivammathur/php-src-backports

Commenical
- https://www.zend.com/services/php-long-term-support
- https://www.cloudlinux.com/features/#hardened-php
- https://www.freexian.com/lts/php/
