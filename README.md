# [Cache](http://pfinal.cn)

缓存

PHP交流 QQ 群：`16455997`

环境要求：PHP >= 5.3

使用 [composer](https://getcomposer.org/)

  ```shell
composer require pfinal/cache
  ```

示例

  ```php
<?php

require 'vendor/autoload.php';

$fileCache = new \PFinal\Cache\FileCache();

$fileCache->set('name', 'Ethan', 60); //缓存60秒

echo $fileCache->get('name');

  ```