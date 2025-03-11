FROM python:latest

ADD . /composeapp

WORKDIR /composeapp

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]