FROM python:3.11-bullseye

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . /usr/src/app

RUN pip3 install --no-cache-dir -r requirements.txt

WORKDIR /usr/src/app/core

EXPOSE 5000

CMD ["python3", "app.py"]
