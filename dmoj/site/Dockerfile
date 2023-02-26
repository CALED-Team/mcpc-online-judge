FROM ninjaclasher/dmoj-base:latest

EXPOSE 8000

RUN pip install django-ses==3.3.0

ENTRYPOINT uwsgi --ini uwsgi.ini
