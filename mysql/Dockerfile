FROM mysql:latest

RUN ls -l

COPY . /workspace

WORKDIR /workspace

ENV MYSQL_DATABASE university

ENV MYSQL_ROOT_PASSWORD=password

COPY ./script.sql /docker-entrypoint-initdb.d/
