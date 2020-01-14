# DRF Docker Scaffolding

# Quickstart in Development

```
docker-compose up -d
docker-compose run web python manage.py migrate
docker-compose run web python manage.py createsuperuser
docker-compose restart
```

