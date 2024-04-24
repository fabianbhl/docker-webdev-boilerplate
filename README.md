# nginx, PHP & MySQL

My standard setup for a docker environment with nginx, PHP and MySQL.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Build and start the containers:

    ```shell
    docker-compose up -d
    ```

2. Access the web/index.php:

    Open your web browser and navigate to `http://localhost:8000`.

## Configuration

PHP version and MySQL settings can be set in .env file.