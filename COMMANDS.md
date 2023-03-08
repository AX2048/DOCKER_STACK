COMMANDS ::

```
docker pull alex501020/ahab:dev

docker compose up

docker compose run --rm  certbot certonly --webroot --webroot-path /var/www/certbot/ -d py2.ponomarev-aa.ru

docker compose restart

docker compose run --rm certbot renew
```