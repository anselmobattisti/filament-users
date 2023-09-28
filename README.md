# Filament users

User Resource For FilamentPHP Admin Dashboard

## Installation

```bash
composer require tomatophp/filament-users
```
after install your package please run this command

## Publish Assets

you can publish config file by use this command

```bash
php artisan vendor:publish --tag="filament-users-config"
```

you can publish views file by use this command

```bash
php artisan vendor:publish --tag="filament-users-views"
```

you can publish languages file by use this command

```bash
php artisan vendor:publish --tag="filament-users-lang"
```

you can publish migrations file by use this command

```bash
php artisan vendor:publish --tag="filament-users-migrations"
```

## Publish Resource

you can publish the resource to your project

```bash
php artisan filament-user:publish
```

it will publish the resource to your project

than go to `filament-user.php` config file and change the `publish_resource` to `true`

## Support

you can join our discord server to get support [TomatoPHP](https://discord.gg/Xqmt35Uh)

## Docs

you can check docs of this package on [Docs](https://docs.tomatophp.com/plugins/laravel-package-generator)

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Security

Please see [SECURITY](SECURITY.md) for more information about security.

## Credits

- [Tomatophp](mailto:info@3x1.io)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
