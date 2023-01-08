## Docker-compose para Laravel 8.0 con PHP 8

Esta configuración cuentan con:

- PHP a travez de FPM (app)
- PHP CLI (cli)
- Servidor Nginx (web)
- Servidor de BD Mariadb (mariadb)

## Ejecutar servicios

```shell
    $> docker-compose up -d
```

## Ejecutar servicios de forma individual

```shell
    $> docker-compose up {service}
```

## Configuración docker

Esta configuración es una implementación de @dportales [https://github.com/apscreativas/laravel8-docker](https://github.com/apscreativas/laravel8-docker) 
visitar el repositorio original para más detalles y actualizaciones.
