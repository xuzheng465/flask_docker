FROM python:3.7.2-stretch

#Set the working directory to /app
WORKDIR /app

ADD . /app

RUN pip install -r requirements.txt

CMD ["uwsgi", "app.ini"]