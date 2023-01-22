FROM python:3.9.1

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app

COPY Data_Insertion.py Data_Insertion.py

ENTRYPOINT [ "python" , "Data_Insertion.py"]