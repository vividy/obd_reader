FROM python:3.6-slim

RUN mkdir /code

# Go to code directory
WORKDIR /code

COPY requirements.txt /code/
RUN pip install -r requirements.txt

# Copy code to docker container
COPY . /code/
