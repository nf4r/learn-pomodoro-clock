FROM python:3.6-slim
ENV PYTHONUNBUFFERED 1
ENV APP_DIR /app
WORKDIR $APP_DIR

COPY requirements.txt .

RUN pip install -r requirements.txt --no-cache-dir

COPY . .

VOLUME [ "/app" ]
