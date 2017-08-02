# Laravel Languages

## Installation

Require this package, with [Composer](https://getcomposer.org/), in the root directory of your project.

``` bash
$ composer require faustbrian/laravel-languages
```

To get started, you'll need to publish the vendor assets and migrate:

```bash
php artisan vendor:publish --provider="BrianFaust\Languages\LanguagesServiceProvider" && php artisan migrate
```

Now you can seed the languages into the database like this.

```bash
php artisan languages:seed
```

## Testing

``` bash
$ phpunit
```

## Security

If you discover a security vulnerability within this package, please send an e-mail to Brian Faust at hello@brianfaust.me. All security vulnerabilities will be promptly addressed.

## Credits

- [Brian Faust](https://github.com/faustbrian)
- [All Contributors](../../contributors)

## License

[MIT](LICENSE) © [Brian Faust](https://brianfaust.me)
