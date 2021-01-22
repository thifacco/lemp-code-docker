# Ambiente LEMP com DOCKER
Ambiente de desenvolvimento Linux - Nginx - MySQL - PHP-FPM

## Requisitos
1. Instalar o [Docker Desktop](https://www.docker.com/products/docker-desktop)

## Iniciar os containers
```
cd lemp-env-docker
docker-compose up -d
```

## Conectar no MySQL pelo container
```
docker-compose exec mysql bash
cd /bitnami/mysql
mysql -u root -p
[senha vazia]
```

## Referências
- [PILHA LEMP](https://www.linode.com/pt/marketplace/apps/linode/lemp/)
- [PHP-FPM](https://hub.docker.com/r/bitnami/php-fpm)
- [NGNIX](https://hub.docker.com/r/bitnami/nginx)
- [MySQL](https://hub.docker.com/r/bitnami/mysql)
