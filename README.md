# LaravelGUI

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

GUI version of the laravel artisan CLI.
supports PSR-4.

## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practices by being named the following.

```
bin/        
config/
src/
tests/
vendor/
```


## Install

Via Composer

``` bash
$ composer require Sarps/LaravelGUI
```

## Usage

``` php
$skeleton = new Sarps\LaravelGUI();
echo $skeleton->echoPhrase('Hello, League!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email esarpong51@gmail.com instead of using the issue tracker.

## Credits

- [Emmanuel Sarpong][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/Sarps/LaravelGUI.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/Sarps/LaravelGUI/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/Sarps/LaravelGUI.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/Sarps/LaravelGUI.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/Sarps/LaravelGUI.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/Sarps/LaravelGUI
[link-travis]: https://travis-ci.org/Sarps/LaravelGUI
[link-scrutinizer]: https://scrutinizer-ci.com/g/Sarps/LaravelGUI/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/Sarps/LaravelGUI
[link-downloads]: https://packagist.org/packages/Sarps/LaravelGUI
[link-author]: https://github.com/Sarps
[link-contributors]: ../../contributors