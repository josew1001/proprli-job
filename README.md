<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions">
    <img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
  </a>
</p>

# 🚀 Dockerized Laravel & Vue.js App with PostgreSQL

Este repositório contém a implementação de um ambiente de desenvolvimento **Dockerizado** para um projeto baseado em **Laravel, Vue.js e PostgreSQL**.

## 🛠️ Tecnologias Utilizadas
- **Laravel** (Backend)
- **Vue.js** (Frontend)
- **PostgreSQL** (Banco de Dados)
- **Docker** (Gerenciamento de Containers)
- **Nginx** (Servidor Web)

## 📥 Instalação

## 🐳 Configuração do Docker
- **Subir os containers** 
$ docker-compose up --build -d
- **Acessar o container**
$ docker exec -it Laravel_php /bin/sh

Dentro deste container, agora você pode executar todos os comandos como se estivesse em um ambiente local.

- **Instalar dependências do Composer**
$ composer install
- **Gerar a chave da aplicação**
$ php artisan key:generate

- **Executar migrações do banco**
$ php artisan migrate

- **Executar App**
$ npm run dev
