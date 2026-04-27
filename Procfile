release: python manage.py migrate --no-input
web: python manage.py collectstatic --no-input && gunicorn config.wsgi:application --bind 0.0.0.0:$PORT
