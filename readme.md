# myLaravel
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
