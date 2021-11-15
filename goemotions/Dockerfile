FROM python:3.7

WORKDIR /goemotions
ADD ./docker-run.sh /goemotions
ADD ./requirements.txt /goemotions

WORKDIR /
RUN goemotions/docker-run.sh
