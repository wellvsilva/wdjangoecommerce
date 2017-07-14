release: python manage.py migrate
release: python manage.py createsuperuser
web: gunicorn djangoecommerce.wsgi --log-file -