# Docker Local WordPress

A Docker-based local development environment for WordPress.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone this repository
2. Run `docker-compose up -d`
3. Access WordPress at `http://localhost:8000`

## Configuration

- WordPress runs on port 8000
- MySQL runs on port 3306
- phpMyAdmin is available at `http://localhost:8080`

## Project Structure

- `docker-compose.yml`: Main Docker configuration
- `php.ini/`: PHP configuration files

## Features

- WordPress latest version
- MySQL 5.7 database
- phpMyAdmin for database management
- Custom PHP configuration support
- Persistent volume for database storage

## Development

To stop the containers:
```bash
docker-compose down
```

To view logs:
```bash
docker-compose logs -f
```

## Security Notes

- This is a development environment and should not be used in production
- Default passwords are used for demonstration purposes
- In a production environment, you should:
  - Use strong passwords
  - Enable SSL/TLS
  - Configure proper security measures 