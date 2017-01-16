# OpenShift Nginx PHP-FPM Cartridge

Nginx updated to 1.6.2 with PHP 5.3/5.4/5.5. ioncube 6.0.8

## Example Usage

### PHP Version
https://cartreflect-claytondev.rhcloud.com/github/potalaleonardo/openshift-nginx-php-fpm?v=5.4

## User-defined configuration

Place your nginx .conf files inside config/nginx.d/. It will be include()ed from "http" scope.
Place your php-fpm .conf files inside config/php-fpm.d/. It will be include()ed from main php-fpm.conf file.