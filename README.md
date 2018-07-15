# upload-image
[![Latest Stable Version](https://poser.pugx.org/fts/upload-image/v/stable)](https://packagist.org/packages/fts/upload-image)
[![Total Downloads](https://poser.pugx.org/fts/upload-image/downloads)](https://packagist.org/packages/fts/upload-image)
[![License](https://poser.pugx.org/fts/upload-image/license)](https://packagist.org/packages/fts/upload-image)

This package allows you to easily handle uploaded files
* Support add watermark
# Install
Install the `upload-image` package with composer:

    composer require fts/upload-image
### Publish Config
    php artisan vendor:publish
### Service Provider
Open `config/app.php` and add a new item to the providers array:
    
    fts\UploadImageServiceProvider.php::class
# Example Usage
    upload_image($key, $fileName='');