makemigration: python manage.py makemigration simplesocial
release: python manage.py migrate
web: gunicorn simplesocial.wsgi
