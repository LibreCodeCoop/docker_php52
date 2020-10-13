# PHP 5.2.17 + Apache 2.2.22 + xdebug

Run PHP 5.2.17 + Apache 2.2.22 in docker environment.

## Instructions

put the source of legacy project in folder `public-html`.

The Apache server is runing inside service `php52`, changhe the bind of ports in `docker-compose.yml`

If need put settings of legacy project, I recommend to put in `.env` file and use in the project calling the native PHP funcion `getenv`.

OBS: The xdebug is enabled