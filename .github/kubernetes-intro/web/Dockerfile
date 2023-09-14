FROM ubuntu
RUN apt-get -y update
RUN apt-get install -y nginx
RUN    mkdir app 
RUN    echo "working" >> /app/homework.html 
RUN    chown -R 1001:1001 /app

WORKDIR /app

CMD ["nginx"]

EXPOSE 8000
