![:package](:hero)

# :package

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Total Downloads][ico-downloads]][link-downloads]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-build]][link-build]
[![StyleCI][ico-styleci]][link-styleci]
[![PhpStan][ico-phpstan]][link-phpstan]

Short description of the package. What does it do and why should people download
it? Brag a bit but don't exaggerate. Talk about what's to come and tease small
pieces of functionality.

> :namespace
> :package
> :styleci
> :hero

## Installation
You can install this package via [Composer](http://getcomposer.org):

```bash
$ composer require sven/:package
```

### Registering the service provider
> Is this a Laravel package?

Next, add the `ServiceProvider` to your `providers` array in `config/app.php`:

```php
'providers' => [
    ...
    Sven\:namespace\ServiceProvider::class,
];
```

If you would like to load this package in certain environments only, take a look
at [`sven/env-providers`](https://github.com/svenluijten/env-providers).

## Usage
Some examples of the code. How should people use it, what options does this package
provide? Should people be wary of some functionality?

```php
Maybe some code?
```

## Contributing
All contributions (pull requests, issues and feature requests) are
welcome. Make sure to read through the [CONTRIBUTING.md](CONTRIBUTING.md) first,
though. See the [contributors page](../../graphs/contributors) for all contributors.

## License
`sven/:package` is licensed under the MIT License (MIT). Please see the
[license file](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/sven/:package.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-green.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/sven/:package.svg?style=flat-square
[ico-build]: https://img.shields.io/github/actions/workflow/status/svenluijten/:package/run-tests.yml?branch=main&style=flat-square
[ico-styleci]: https://styleci.io/repos/:styleci/shield
[ico-phpstan]: https://img.shields.io/badge/phpstan-enabled-blue.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/sven/:package
[link-downloads]: https://packagist.org/packages/sven/:package/stats
[link-build]: https://github.com/svenluijten/:package/actions/workflows/run-tests.yml
[link-styleci]: https://styleci.io/repos/:styleci
[link-phpstan]: https://github.com/phpstan/phpstan
