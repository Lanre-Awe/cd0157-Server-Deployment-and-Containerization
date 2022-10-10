FROM python:3.7.2-slim

COPY . /app
WORKDIR /app

RUN pip install --upgrade pip
RUN pip install flask


ENTRYPOINT ["python", "app.py"]

https://dev-s04591m9.us.auth0.com/authorize?audience=coffeeShop&response_type=token&client_id=OBziBJZowenIVtahj4n6d8y1ymmQYUhx&redirect_uri=http://127.0.0.1:8100