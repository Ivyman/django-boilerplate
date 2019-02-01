### Setup:
1. Run conteiner `$ docker-compose up`
2. Login to running conteiner `$ docker exec -it <container_hash> bash`
3. Run migrations `$ python manage.py migrate`
4. Create superuser `$ python manage.py createsuperuse`
5. Start up `$ python manage.py runserver 0.0.0.0:8000`

### This project includes:
1. The Django Debug Toolbar
2. Multiple settings modules setup for easily deploying