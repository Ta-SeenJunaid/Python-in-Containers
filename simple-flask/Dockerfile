FROM python:3.8

WORKDIR /usr/src/app

COPY requirements.txt .

RUN pip3 install -r requirements.txt

COPY hello.py .

EXPOSE 5000

CMD python3 hello.py