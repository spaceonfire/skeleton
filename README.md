# :package_name

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]
[![Code Coverage][ico-coverage]][link-actions]
[![Build Status][ico-build-status]][link-actions]

**Note:** Replace `:author_name` `:author_username` `:author_website` `:author_email` `:vendor` `:package_name` `:package_description` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can run `$ php prefill.php` in the command line to make all replacements at once. Delete the file prefill.php as well.

This is where your description should go. Try to limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practices by being named the following.

```
bin/
build/
docs/
config/
src/
tests/
vendor/
```

## Install

Via Composer

```bash
$ composer require :vendor/:package_name
```

## Usage

```php
$skeleton = new spaceonfire\Skeleton\SkeletonClass();
echo $skeleton->echoPhrase('I\'m on fire!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

```bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email :author_email instead of using the issue tracker.

## Credits

- [:author_name][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/:vendor/:package_name.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/:vendor/:package_name.svg?style=flat-square
[ico-coverage]: https://img.shields.io/endpoint?style=flat-square&url=https%3A%2F%2Fgist.githubusercontent.com%2Fhustlahusky%2Fd62607c1a2e4707959b0142e0ea876cd%2Fraw%2F:vendor-:package_name.json
[ico-build-status]: https://github.com/:vendor/:package_name/workflows/Build%20Pipeline/badge.svg
[link-packagist]: https://packagist.org/packages/:vendor/:package_name
[link-downloads]: https://packagist.org/packages/:vendor/:package_name
[link-author]: https://github.com/:author_username
[link-contributors]: ../../contributors
[link-actions]: ../../actions
