FROM python:3.11.2-alpine

WORKDIR /usr/src/app

COPY ./app/requirements.txt ./requirements.txt
RUN pip3 install -r requirements.txt

COPY ./app .

CMD ["python3", "app.py" ]