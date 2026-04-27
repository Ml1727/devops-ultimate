FROM python:3.9-slim

WORKDIR /app

COPY app/ /app
COPY app/requirements.txt /app

RUN pip install -r requirements.txt

CMD ["python", "app.py"]
