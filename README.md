# upload-image
[![Latest Stable Version](https://poser.pugx.org/fts/upload-image/v/stable)](https://packagist.org/packages/fts/upload-image)
[![Total Downloads](https://poser.pugx.org/fts/upload-image/downloads)](https://packagist.org/packages/fts/upload-image)
[![License](https://poser.pugx.org/fts/upload-image/license)](https://packagist.org/packages/fts/upload-image)

# 功能
* 上传图片
* 添加水印
# 安装
    composer require fts/upload-image
### 发布配置文件
    php artisan vendor:publish
### 添加服务提供者
打开 `config/app.php` 并添加以下内容到 providers 数组:
    
    fts\UploadImage\UploadImageServiceProvider.php::class
# 使用
    upload_image($key, $fileName='');
