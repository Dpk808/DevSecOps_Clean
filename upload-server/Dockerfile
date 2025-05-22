FROM python:3.13-slim

WORKDIR /app

COPY app.py .

RUN pip install --no-cache-dir flask && \
    mkdir /uploads

VOLUME ["/uploads"]

CMD ["python", "app.py"]
