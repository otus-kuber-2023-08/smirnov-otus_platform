FROM nginx
RUN mkdir /app
COPY config.conf /etc/nginx/conf.d/default.conf
COPY . /app/
ARG UID=1001
WORKDIR /app
EXPOSE 8000
