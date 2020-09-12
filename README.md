# Random
生成随机数的插件

## 安装
```php
composer require bang/Random
```


## 用法
``` php
  <?php
        Random::alnum(6);//生成数字和字母
        Random::alpha(6);//仅生成字符
        Random::numeric(6);//生成指定长度的随机数字
        Random::nozero(6);//数字和字母组合的随机字符串
        Random::chinese(6);//6个汉字
        Random::uuid(6);//获取全球唯一标识
    
```

