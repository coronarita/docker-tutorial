# FROM ubuntu

# RUN apt-get update && apt-get install -y python3 python3-pip
FROM python:3-alpine

WORKDIR /app

COPY . /app
# RUN pip3 install -r requirements.txt
RUN pip install -r requirements.txt

RUN echo "Hello world" \
    > /app/hello.txt

# CMD ["python3", "main.py"]
CMD ["python", "main.py"]