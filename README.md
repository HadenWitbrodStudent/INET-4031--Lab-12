INET-4031 Lab 12 – Docker App
# Overview

This project runs a multi-container app using Docker Compose:

Apache (web) – handles requests
Flask (app) – backend API
MariaDB (db) – database

# Setup

1. git clone https://github.com/HadenWitbrodStudent/INET-4031--Lab-12.git
2. cd INET-4031--Lab-12
3. cp .env.example .env
4. docker compose up --build

# Access

Open:

http://localhost

# Features

REST API (/api/tickets)
Persistent data (Docker volume)
Internal networking via service names
Health checks for services

# Useful Commands
docker compose ps
docker compose logs <service>
docker compose down
docker compose down -v

# Author

Haden Witbrod
INET-4031
