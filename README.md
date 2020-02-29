# Backspace Homepage

## Local Setup

1. run `docker-compose up -d`
2. enter web container: `docker-compose exec web /bin/bash`
3. run migrations: `python manage.py migrate`
4. create superuser : `python manage.py createsuperuser`
5. visit http://localhost:8000
