# Ambiente LEMP com DOCKER
Ambiente de desenvolvimento Linux - Nginx - MySQL - PHP-FPM

## Requisitos
1. Instalar o [Docker Desktop](https://www.docker.com/products/docker-desktop)

## Iniciar os containers
```
cd lemp-env-docker
docker-compose up -d
```

## Criar o banco de dados `chatbot_api`
Opção 1: criar o DB diretamente pelo container do docker
```
docker-compose exec mysql bash
cd /bitnami/mysql
mysql -u root -p
create database chatbot_api;
```

Opção 2: criar o DB através de um client MySQL
```
host: 127.0.0.1
port: 3306
user: root
pass: 
```

## Referências
- [PILHA LEMP](https://www.linode.com/pt/marketplace/apps/linode/lemp/)
- [PHP-FPM](https://hub.docker.com/r/bitnami/php-fpm)
- [NGNIX](https://hub.docker.com/r/bitnami/nginx)
- [MySQL](https://hub.docker.com/r/bitnami/mysql)
