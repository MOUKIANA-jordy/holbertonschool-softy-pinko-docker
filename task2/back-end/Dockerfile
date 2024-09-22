FROM python:3.8-slim

WORKDIR /app

COPY . /app

RUN apt-get update && apt-get install -y python3 python3-pip && \
    pip install --no-cache-dir flask

EXPOSE 5252

ENV NAME World

CMD ["python3", "api.py"]
