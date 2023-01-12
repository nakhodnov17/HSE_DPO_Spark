FROM python:3.11-slim

RUN mkdir /root/app
WORKDIR /root/app

COPY ./example.py ./
RUN chmod +x example.py

ENV SECRET_KEY hello

CMD ["python3", "example.py"]
