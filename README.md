# 关于

laravel自动提示补全功能,提取自ide-helper

原插件使用步骤:
```
1.composer
2.容器注册
3.artisan
```


现在使用方法:
```
wget https://raw.githubusercontent.com/piaohan/laravel_ide_helper/master/_ide_helper.php
```


---

>我很懒...一般这样够用了 ^_^

---
# 对于想用全些的 可以这么用

## 1.composer 引入包
```
composer require barryvdh/laravel-ide-helper doctrine/dbal
```
或者只用于`开发环境`
```
composer require barryvdh/laravel-ide-helper doctrine/dbal  --dev 
```

## 2.容器注册
config/app.php
```
Barryvdh\LaravelIdeHelper\IdeHelperServiceProvider::class,
```
## 3.artisan
```
php artisan ide-helper:generate
php artisan ide-helper:model
```
---
骚年,准备好了,开始感受吧...呵呵
