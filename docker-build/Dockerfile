FROM python:3.8

RUN apt-get install wget

ENV FLASK_APP=run.py
ENV FLASK_ENV=development
ENV FLASK_RUN_PORT=5000

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

ENTRYPOINT [ "flask", "run", "--host=0.0.0.0" ]

