FROM mysql:5.7

RUN mkdir -p /src/app

WORKDIR /src/app

COPY . /src/app

EXPOSE 3306

ADD schema.sql /docker-entrypoint-initdb.d
