FROM python:slim

RUN apt-get update \
    && apt-get install -y \
        cron
CMD cron -f
