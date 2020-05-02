  FROM ubuntu
  maintainer kunalsharma19997@gmail.com
  RUN apt-get update
  RUN apt install python3-pip -y
  RUN apt-get install libmysqlclient-dev -y
  RUN pip3 install django
  RUN pip3 install mysqlclient
  RUN mkdir kunal
  COPY kunal /kunal
  WORKDIR kunal
  #CMD python3 manage.py runserver 0.0.0.0:8000
