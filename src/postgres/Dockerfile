FROM postgres:alpine

ENV POSTGRES_PASSWORD=pdf

ENV POSTGRES_USER=pdf

ENV POSTGRES_DB=pdf

COPY ./sql /docker-entrypoint-initdb.d
