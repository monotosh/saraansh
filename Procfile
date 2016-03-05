web: gunicorn config.wsgi:application
worker: newrelic-admin run-program celery worker --app=saraansh.taskapp --loglevel=info
