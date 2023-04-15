# lab-laravel

## Travail à faire 


- Installation de laravel v.10
- Comprendre l'architecure de laravel
- Présentation google slide
  - https://docs.google.com/presentation/d/1AtqnL9d_2oLQBtV0DrOcQoA3_ZxcgJCb3kD0cKygwXs/edit?usp=sharing

## Installation

### Configuration de PHP 

````conf
[PHP]
extension=fileinfo
extension=pdo_mysql
extension=zip
````

### Laravel

````bash
composer create-project laravel/laravel lab-laravel
````

````bash
composer global require laravel/installer
laravel new lab-laravel
php artisan serve
````



## Références 
- https://laravel.com/docs/10.x