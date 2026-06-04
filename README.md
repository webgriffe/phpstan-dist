# webgriffe/phpstan-dist

PHPStan phar distribution for Webgriffe projects.

Provides the `phpstan` binary via Composer without pulling in PHPStan's full dependency tree.

## Installation

```bash
composer require --dev webgriffe/phpstan-dist
```

## Usage

```bash
vendor/bin/phpstan analyse
```

## Versioning

Versions mirror [PHPStan upstream releases](https://github.com/phpstan/phpstan/releases).

## How it works

This package is automatically updated by [webgriffe/php-tools-dist](https://github.com/webgriffe/php-tools-dist).
When a new PHPStan release is published, the phar is downloaded and a new tagged version is pushed here within 24 hours.
