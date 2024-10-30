FROM python:3.12-slim

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /home/notebook/data-engineering-test

COPY solution/requirements.txt ./requirements.txt

RUN pip install --no-cache-dir -r requirements.txt
