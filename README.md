# ModSecurity using NGINX (Docker)

Clone repository
```
git clone https://github.com/Ventustium/nginx-modsecurity.git
```

Change directory
```
cd ./nginx-modsecurity
```

Docker Compose Up
```
docker compose up
```

Cek Container Status
```
docker ps

CONTAINER ID   IMAGE                           COMMAND                  CREATED         STATUS        PORTS                               NAMES
12cb2629890e   owasp/modsecurity-crs:3-nginx   "/docker-entrypoint.…"   3 seconds ago   Up 1 second   0.0.0.0:80->80/tcp, :::80->80/tcp   modsecurity-nginx
27a961cfff65   vulnerables/web-dvwa            "/main.sh"               3 seconds ago   Up 1 second   80/tcp                              dvwa
```