USAGE LOCAL DEVELOPMENT CONTAINS DJANGO AND POSTGIS DATABASE
```
docker-composer up -d --build
```

USAGE IN PRODUCTION CONTAINT NGINX DJANGO AND POSTGIS DATABASE
```
docker-composer -f docker-compose.prod.yml up -d --build
```
