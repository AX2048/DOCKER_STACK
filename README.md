## DOCKER_STACK

NGINX + CERTBOT | DJANGO & UVICORN
---

http://uvicorn.ponomarev-aa.ru

-> python_back

http://py1.ponomarev-aa.ru/

-> https://hub.docker.com/repository/docker/alex501020/ahab/general


http://py2.ponomarev-aa.ru/

-> https://hub.docker.com/repository/docker/alex501020/ishmael/general

---

For CERTBOT::
```
     - ./certbot/www/:/var/www/certbot/:rw
     - ./certbot/conf/:/etc/letsencrypt/:rw
```

Create: 

```
/certbot/www/
/certbot/conf/
```

HTTPS using Nginx and Let's encrypt in Docker
https://mindsers.blog/post/https-using-nginx-certbot-docker/

---

Сервер может быть не запущен, но у тебя поучится запустить всё самому)