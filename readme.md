Nextras Migrations
==================

[![Build Status](https://travis-ci.org/nextras/migrations.svg?branch=master)](https://travis-ci.org/nextras/migrations)
[![Downloads this Month](https://img.shields.io/packagist/dm/nextras/migrations.svg?style=flat)](https://packagist.org/packages/nextras/migrations)
[![Stable Version](https://poser.pugx.org/nextras/migrations/v/stable)](https://packagist.org/packages/nextras/migrations)
[![Code coverage](https://img.shields.io/coveralls/nextras/migrations.svg?style=flat)](https://coveralls.io/r/nextras/migrations)

For more information read **[documentation](https://nextras.org/migrations/docs)**.

**Supported databases:**
* PostgreSQL
* MySQL

**Supported DBALs:**
* [Nextras DBAL](https://github.com/nextras/dbal)
* [Nette Database](https://github.com/nette/database)
* [Doctrine DBAL](https://github.com/doctrine/dbal)
* [dibi](https://github.com/dg/dibi)


Development & Running Tests in Docker
-------------------------------------
1. Start containers
    ```bash
    docker-compose up --always-recreate-deps --build --force-recreate
    ```
1. Install dependencies
    ```bash
    docker-compose exec php-fpm bash
    composer install
    ```
1. Create `./tests/*.ini` files from samples `./tests/*.docker.ini` and run `./tests/run-integration.sh`


License
-------

*Based on [Clevis\Migration](https://github.com/Clevis/Migration) by Petr Procházka and further improved.*

New BSD License. See full [license](license.md).
