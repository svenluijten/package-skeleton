![package](https://cloud.githubusercontent.com/assets/11269635/14202863/c0b21296-f7fa-11e5-9ef1-2f684537ee24.jpg)

# Package

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Total Downloads][ico-downloads]][link-downloads]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Code Climate][ico-codeclimate]][link-codeclimate]
[![Code Quality][ico-quality]][link-quality]
[![SensioLabs Insight][ico-insight]][link-insight]

Short description of the package. What does it do and why should people download
it? Brag a bit but don't exaggerate. Talk about what's to come and tease small
pieces of functionality.

## Installation
Via [composer](http://getcomposer.org):

```bash
$ composer require sven/package --prefer-source
```

Or add the package to your dependencies in `composer.json` and run
`composer update` to download the package:

```json
{
    "require": {
        "sven/package": "*"
    }
}
```

> Is this a Laravel package?

Next, add the `PackageServiceProvider` to your `providers` array in `config/app.php`:

```php
// config/app.php
'providers' => [
    ...
    Sven\Moretisan\MoretisanServiceProvider::class,
];
```

## Usage
Some examples of the code. How should people use it, what options does this package
provide? Should people be wary of some functionality?

**More in-depth documentation can be found on the [wiki](../../wiki).**

## Contributing
All contributions (in the form on pull requests, issues and feature-requests) are
welcomed. See the [contributors page](../../graphs/contributors) for all contributors.

## License
`sven/package` is licenced under the MIT License (MIT). Please see the
[license file](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/sven/package.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-green.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/sven/package.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/svenluijten/package.svg?style=flat-square
[ico-codeclimate]: https://img.shields.io/codeclimate/github/svenluijten/package.svg?style=flat-square
[ico-quality]: https://img.shields.io/scrutinizer/g/svenluijten/package.svg?style=flat-square
[ico-insight]: https://img.shields.io/sensiolabs/i/insight-id.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/sven/package
[link-downloads]: https://packagist.org/packages/sven/package
[link-travis]: https://travis-ci.org/svenluijten/package
[link-codeclimate]: https://codeclimate.com/github/svenluijten/package
[link-quality]: https://scrutinizer-ci.com/g/svenluijten/package/?branch=master
[link-insight]: https://insight.sensiolabs.com/projects/insight-id
