# Enhanced Laravel integration with a lot more PostgreSQL specific capabilities.

[![Latest Version on Packagist](https://img.shields.io/packagist/v/tpetry/laravel_postgresql_enhanced.svg?style=flat-square)](https://packagist.org/packages/tpetry/laravel_postgresql_enhanced)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/tpetry/laravel_postgresql_enhanced/run-tests?label=tests)](https://github.com/tpetry/laravel_postgresql_enhanced/actions?query=workflow%3ATests+branch%3Amaster)
[![GitHub Code Style Action Status](https://img.shields.io/github/workflow/status/tpetry/laravel_postgresql_enhanced/Check%20&%20fix%20styling?label=code%20style)](https://github.com/tpetry/laravel_postgresql_enhanced/actions?query=workflow%3A"Check+%26+fix+styling"+branch%3Amaster)
[![Total Downloads](https://img.shields.io/packagist/dt/tpetry/laravel_postgresql_enhanced.svg?style=flat-square)](https://packagist.org/packages/tpetry/laravel_postgresql_enhanced)

[](delete) 1) manually replace `tpetry, tpetry, auhor@domain.com, tpetry, tpetry, Vendor Name, laravel-postgresql-enhanced, laravel_postgresql_enhanced, laravel_postgresql_enhanced, PostgresqlEnhanced, Enhanced Laravel integration with a lot more PostgreSQL specific capabilities.` with their correct values
[](delete) in `CHANGELOG.md, LICENSE.md, README.md, ExampleTest.php, ModelFactory.php, PostgresqlEnhanced.php, PostgresqlEnhancedCommand.php, PostgresqlEnhancedFacade.php, PostgresqlEnhancedServiceProvider.php, TestCase.php, composer.json, create_laravel_postgresql_enhanced_table.php.stub`
[](delete) and delete `configure-laravel_postgresql_enhanced.sh`

[](delete) 2) You can also run `./configure-laravel_postgresql_enhanced.sh` to do this automatically.

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Support us

[<img src="https://github-ads.s3.eu-central-1.amazonaws.com/package-laravel_postgresql_enhanced-laravel.jpg?t=1" width="419px" />](https://spatie.be/github-ad-click/package-laravel_postgresql_enhanced-laravel)

We invest a lot of resources into creating [best in class open source packages](https://spatie.be/open-source). You can support us by [buying one of our paid products](https://spatie.be/open-source/support-us).

We highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using. You'll find our address on [our contact page](https://spatie.be/about-us). We publish all received postcards on [our virtual postcard wall](https://spatie.be/open-source/postcards).

## Installation

You can install the package via composer:

```bash
composer require tpetry/laravel_postgresql_enhanced
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --provider="Tpetry\PostgresqlEnhanced\PostgresqlEnhancedServiceProvider" --tag="laravel_postgresql_enhanced-migrations"
php artisan migrate
```

You can publish the config file with:
```bash
php artisan vendor:publish --provider="Tpetry\PostgresqlEnhanced\PostgresqlEnhancedServiceProvider" --tag="laravel_postgresql_enhanced-config"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

```php
$laravel_postgresql_enhanced = new Tpetry\PostgresqlEnhanced();
echo $laravel_postgresql_enhanced->echoPhrase('Hello, Spatie!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [tpetry](https://github.com/tpetry)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
