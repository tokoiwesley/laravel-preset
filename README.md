# Laravel Preset

This is a package for creating a custom frontend (JavaScript and CSS) scaffolding in Laravel other than the default ( [Bootstrap][1] and [Vue][2]) scaffolding that ships with Laravel. 

This package is inspired by [How to Create Custom Laravel Presets] series on [Laracasts][3]. You may use the package in your projects if you find it useful since I have tailored the custom frontend scaffolding included to my own personal needs. You may as well fork the project to add your personal preferences if you so wish.

## Installation

To install the package use the following command:

```
composer require tokoiwesley/laravel-preset
```

## Usage

*Note*: This package is compatible with Laravel 5.7+ due to the [flattening of the `resources/assets` directory](https://twitter.com/taylorotwell/status/1024391862445113344).

Use the `preset` artisan command in combination with the `custom` option to create the custom scaffolding in your application. Next, run "npm install && npm run dev" to compile the custom scaffolding.

```
php artisan preset custom

npm install && npm run dev
```

That's all!

## License

This project is licensed under the terms of the [MIT license](LICENSE).

[1]: https://getbootstrap.com/
[2]: https://vuejs.org/
[3]: https://laracasts.com/series/how-to-create-custom-presets