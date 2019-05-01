FROM python:3

RUN mkdir /code

## upgrade install
#RUN apt-get update && apt-get upgrade -y
#RUN python3 -m pip install --upgrade pip

# Go to code directory
WORKDIR /code

COPY requirements.txt /code/
RUN pip install -r requirements.txt

# Copy code to docker container
COPY . /code/
