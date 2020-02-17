FROM python:3.6

EXPOSE 5000

WORKDIR /app




COPY requirements.txt /app
RUN pip install -r requirements.txt
RUN pip install mysql-connector
#RUN flask run
COPY app.py /app
CMD python app.py
