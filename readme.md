# Lumen 5 with Codeception

In this tutorial, I will show you how to replace default Laravel 5 testing suites with Codeception only.

*[Read online](https://laravelista.com/lessons/lumen-5-with-codeception)*

## Installation

Clone repository to your drive and type in the terminal there:

```
composer install
```

## Configuration

Copy file `.env.example` to `.env` file:

```
cp .env.example .env
```

and change the `APP_KEY` in `.env` to a 32 characters long string.

> If you are lazy, use this `12345678901234567890123456789011`.

## Running

From terminal type:

```
php -S localhost:8000 -t public
```

You should get an address to open in your browser like http://localhost:8000.

## Running tests

From terminal type:

```
vendor/bin/codecept run functional
```
