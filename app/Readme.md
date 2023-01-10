

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

