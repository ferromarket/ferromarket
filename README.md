# FerroMarket

## Estado

### Frontend

[![ci](https://github.com/ferromarket/frontend/actions/workflows/main.yml/badge.svg?event=push)](https://github.com/ferromarket/frontend/actions/workflows/main.yml)

### Backend

[![ci](https://github.com/ferromarket/backend/actions/workflows/main.yml/badge.svg?event=push)](https://github.com/ferromarket/backend/actions/workflows/main.yml)

## Configure system
```
cp .env.example .env
```
Modify the .env file and change the users and passwords.
## Bring up the app
```
docker-compose up -d --build
```
## Bring down the app
```
docker-compose down
```
