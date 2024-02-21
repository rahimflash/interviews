#Dockerfile

FROM python:3.10-slim

WORKDIR /app

RUN pip install --no-cache-dir Flask

COPY ../python-app/ .

EXPOSE 2024

ENV FLASK_APP=hello.py

CMD ["flask", "run", "--host=0.0.0.0", "--port=2024"]
