DOCKER_STAK

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