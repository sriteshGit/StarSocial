makemigration: python manage.py makemigrations simplesocial
release: python manage.py migrate
web: gunicorn simplesocial.wsgi
