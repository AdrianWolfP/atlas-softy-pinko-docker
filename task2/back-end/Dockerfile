FROM ubauntu:lastest

RUN apt-get update
RUN apt-get upgrade
RUN apt-get install -y python3 python3-pip
RUN pip3 install flask

WORKDIR /app
COPY ./api.py /app/api.py

CMD ["python3", "/app/api.py"]