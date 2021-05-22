FROM python:3.9.5

RUN pip install \
    django \
    djangorestframework \
    pygments

WORKDIR /api

COPY ../../../Users/xzone/OneDrive/Рабочий%20стол .

EXPOSE 8000
ENTRYPOINT python manage.py runserver 0.0.0.0:8000