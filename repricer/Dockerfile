FROM python:3.7

RUN apt-get update
RUN apt-get -y install wget ca-certificates libffi-dev python3-psycopg2

COPY requirements.txt ./

RUN pip install --no-cache-dir --upgrade pip
RUN pip install --no-cache-dir -r requirements.txt
