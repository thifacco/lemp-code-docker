# LEMP CODE DOCKER
Ambiente de desenvolvimento composto por Linux - Nginx - MySQL - PHP-FPM

## Requisitos
1. Instalar o [Docker Desktop](https://www.docker.com/products/docker-desktop)

## Iniciar os containers
`docker-compose up -d`

## Criar banco de dados (opcional)
Conectar no MySQL via client com os dados:
```
host: 127.0.0.1
port: 3306
user: root
pass: 
```

Criar o banco de dados:
`create database chatbot_api;`

## Referências
- [PILHA LEMP](https://www.linode.com/pt/marketplace/apps/linode/lemp/)
- [PHP-FPM](https://hub.docker.com/r/bitnami/php-fpm)
- [NGNIX](https://hub.docker.com/r/bitnami/nginx)
- [MySQL](https://hub.docker.com/r/bitnami/mysql)