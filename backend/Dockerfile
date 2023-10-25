FROM python:3.10-alpine3.18

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /backend
COPY . .

EXPOSE 8000

RUN pip install -r req.txt

RUN adduser --disabled-password artem

USER artem