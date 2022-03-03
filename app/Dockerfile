FROM python:slim

RUN apt-get update \
    && apt-get install -y \
        cron \
    && pip3 install poetry
WORKDIR /srv
CMD cron -f
