FROM python:3.9


COPY app/ /app

WORKDIR /app

RUN apt-get update && \
    pip install --upgrade pip && \
    pip install -r requirements.txt

CMD python app.py