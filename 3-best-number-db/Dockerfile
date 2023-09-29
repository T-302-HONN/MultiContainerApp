FROM postgres

ENV POSTGRES_USER "postgres"
ENV POSTGRES_PASSWORD "postgres"
ENV POSTGRES_DB "best-number"

EXPOSE 5432

COPY init.sql /docker-entrypoint-initdb.d/