COMMANDS ::

```
docker compose up

docker compose run --rm  certbot certonly --webroot --webroot-path /var/www/certbot/ -d uvicorn.ponomarev-aa.ru

docker compose restart

docker compose run --rm certbot renew
```