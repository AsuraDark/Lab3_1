heroku stack:set heroku-18
web: gunicorn wsgi:app -b 0.0.0.0:$PORT --chdir flaskapp --timeout 1200
