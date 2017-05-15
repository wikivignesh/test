

web: gunicorn gettingstarted.wsgi --log-file -
manage: python manage.py test
heroku run 
python manage.py runserver
