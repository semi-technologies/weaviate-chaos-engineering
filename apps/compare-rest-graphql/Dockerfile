FROM python:3.9-slim-buster

WORKDIR /workdir

COPY requirements.txt .
RUN pip3 install -r requirements.txt

COPY objects-are-not-deleted.py ./
