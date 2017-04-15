FROM mysql:latest

ENV MYSQL_DATABASE app
ENV MYSQL_PASSWORD user
ENV MYSQL_USER user
ENV MYSQL_ROOT_PASSWORD root

COPY ./custom.cnf /etc/mysql/conf.d
COPY ./init.sql /docker-entrypoint-initdb.d
