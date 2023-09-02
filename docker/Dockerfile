FROM python:3.10-slim-bullseye

WORKDIR /coursework_drf

COPY ./requirements.txt /coursework_drf/

RUN pip install celery

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

COPY ./coursework_drf /coursework_drf/
