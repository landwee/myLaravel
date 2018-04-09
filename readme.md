# myLaravel
#### 开发环境
- 配置ide_helper--项目地址：https://github.com/barryvdh/laravel-ide-helper 直接下载raw文件
##### 部署生产环境
- 优化自动加载
```
composer install --optimize-autoloader
```
- 优化配置加载
```
php artisan config:cache
```
- 优化路由加载
```
php artisan route:cache
```
