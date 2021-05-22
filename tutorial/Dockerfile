FROM python:3.9.5

RUN pip install \
    django \
    djangorestframework \
    pygments

WORKDIR /api

COPY . .

EXPOSE 8000
ENTRYPOINT python manage.py runserver 0.0.0.0:8000