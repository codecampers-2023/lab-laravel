# lab-laravel

## Travail à faire 


- Installation de laravel v.10
- Comprendre l'architecure de laravel
- Présentation google slide
  - https://docs.google.com/presentation/d/1AtqnL9d_2oLQBtV0DrOcQoA3_ZxcgJCb3kD0cKygwXs/edit?usp=sharing

## Présentation

### Références 
- https://www.youtube.com/watch?v=ULs7m9srEj8

## Installation

### Références 
- https://laravel.com/docs/10.x/installation
- https://grafikart.fr/tutoriels/structure-laravel-2113#autoplay
- 

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
## or 
php -S localhost:8080 -t public
````
## Configuration

Le fichier par défaut de Laravel .env contient certaines valeurs de configuration courantes qui peuvent différer selon que votre application s'exécute localement ou sur un serveur Web de production. Ces valeurs sont ensuite récupérées à partir de divers fichiers de configuration Laravel dans le config répertoire à l'aide de la fonction Laravel env.

````conf
APP_NAME=Lab - Laravel
APP_ENV=local
APP_KEY=base64:eacChAqZpfcHflTH9UszddOyTF5jv3QyZcsVWT++dNc=
APP_DEBUG=true
APP_URL=http://localhost
````

### Références 
- https://laravel.com/docs/10.x/configuration


## Structure du répertoire


### Références 
- https://laravel.com/docs/10.x/structure
- https://grafikart.fr/tutoriels/structure-laravel-2113#autoplay
- https://www.youtube.com/watch?v=KoxeKRn2pCk


## Routes

### Références
- https://grafikart.fr/tutoriels/routing-laravel-2114#autoplay

## L'ORM Eloquent
### Références
- https://grafikart.fr/tutoriels/orm-eloquent-laravel-2115#autoplay

## Controllers
### Références
- https://grafikart.fr/tutoriels/controller-laravel-2116#autoplay


## Moteur de template Blade
### Références
- https://grafikart.fr/tutoriels/blade-template-laravel-2117#autoplay

## Valider les données
### Références
- https://grafikart.fr/tutoriels/validation-laravel-2118#autoplay
- https://laravel.com/docs/10.x/validation

## Références 
- https://laravel.com/docs/10.x/installation
- https://grafikart.fr/formations/laravel