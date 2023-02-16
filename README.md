## DOCKER_STAK

---

http://uvicorn.ponomarev-aa.ru

http://py1.ponomarev-aa.ru/

http://py2.ponomarev-aa.ru/

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