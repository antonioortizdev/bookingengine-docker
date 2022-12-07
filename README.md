# Booking Engine Docker
## How to use
### Prepare the images
```bash
cp .env.example .env
```
```bash
docker-compose up -d
```
### Initialize API

```bash
docker-compose exec api composer install
docker-compose exec api php artisan key:generate
```

