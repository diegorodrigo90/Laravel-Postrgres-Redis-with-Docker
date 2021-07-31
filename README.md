# Laravel + Postrgres + Redis with Docker

This is a simple docker-compose stack for laravel development.

## How to use


```bash
git clone https://github.com/diegorodrigo90/Laravel-Postrgres-Redis-with-Docker.git
```

```bash
cd Laravel-Postrgres-Redis-with-Docker
```

```bash
cp .env.example .env
```

Change the variables in **.env**.

Copy you laravel application in **laravel-app** folder at ***root*** path.

```bash
docker-compose up -d
```