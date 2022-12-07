# Booking Engine Docker
## How to use
### Create the containers
```bash
cp .env.example .env
```
```bash
docker-compose up -d
```
### Set API project

```bash
docker-compose exec api composer install
docker-compose exec api php artisan key:generate
```

