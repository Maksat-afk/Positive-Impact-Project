web: bash -c "python manage.py migrate && python manage.py collectstatic --noinput && gunicorn pip_site.wsgi:application"
