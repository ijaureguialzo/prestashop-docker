# PrestaShop

Entorno de prueba de [PrestaShop](https://prestashop.es) con Docker Compose.

## Puesta en marcha

1. Configurar el fichero `.env` partiendo del `env-example`.

2. Arrancar los contenedores:

    ```shell
    make start
    ```

3. Acceso a los servicios:

    - [PrestaShop Frontend](http://localhost:8080)
    - [PrestaShop Backend](http://localhost:8080/backend)
    - [phpMyAdmin](http://localhost:8090)

## Referencias

- [Installing PrestaShop with Docker](https://devdocs.prestashop-project.org/8/basics/installation/environments/docker/)
- [PrestaShop on Docker](https://github.com/PrestaShop/docker)
