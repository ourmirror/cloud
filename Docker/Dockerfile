FROM python:3.8

RUN pip install django
RUN pip install mysqlclient

WORKDIR /django-web

COPY . .

WORKDIR ./django-web

CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000"]

EXPOSE 8000
