### Docker Image for Laravel Projects

[![Docker](https://github.com/antonioanerao/dockerfile-laravel/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/antonioanerao/dockerfile-laravel/actions/workflows/docker-publish.yml)

#### Nginx Version
    1.25.4

#### PHP Version
    8.2.7

#### NODE Version
    18.20.0

### NPM Version
    10.5.0

#### PHP Extensions
    php8.2-fpm
    php8.2-mbstring
    php8.2-soap
    php8.2-gd
    php8.2-xml
    php8.2-intl
    php8.2-dev
    php8.2-curl
    php8.2-zip
    php8.2-imagick
    php8.2-gmp
    php8.2-ldap
    php8.2-bcmath
    php8.2-bz2
    php8.2-phar
    php8.2-mysql
    php8.2-sqlite3
    php8.2-sqlsrv
    php8.2-pdo_sqlsrv

#### Root folder
    /laravel

### How to run

#### Clone this repo
    $ git clone https://github.com/antonioanerao/dockerfile-laravel.git

#### CD to the repo folder
    $ cd dockerfile-laravel

#### Build the docker image
    $ docker build -t laravel .

#### Do you prefer a Docker Image instead?
    https://hub.docker.com/r/antonioanerao/laravel
