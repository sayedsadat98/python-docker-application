FROM python:3

WORKDIR /usr/src/app

COPY requirements.txt .

RUN pip3 install -r requirements.txt

COPY hello.py .

EXPOSE 3000

CMD python3 hello.py