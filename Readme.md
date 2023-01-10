# Skeleton de un entorno dockerizado para proyectos en Symfony

## Servicios

### Servidor NGINX
    imagen: nginx:1.17.8-alpine
### PHP 
    imagen: php:8.1-fpm-buster
### MYSQL
    imagen: mysql:8.0


Los proyectos se deben incluir dentro de la carpeta app




Steps for build the application:

```
- composer create-project symfony/skeleton:"6.2.*" application
- mv replace application/* .
- mueve manualmente el fichero .env y .gitignore y elimina la carpeta application

```

## Dependencies:

Databases dependency: composer require symfony/orm-pack
Templates front: composer require symfony/twig-pack
Debbug: composer require symfony/debug-pack
Bundle: composer require symfony/maker-bundle --dev

