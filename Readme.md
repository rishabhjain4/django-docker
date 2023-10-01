## django-postgres-docker Setup

Initial setup for django with postgres database and developing the project using docker compose.

Edit the ```requirements.txt``` file as required


```
docker-compose up -d --build
docker-compose exec web python manage.py createsuperuser
```