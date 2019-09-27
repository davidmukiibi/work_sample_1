# build an image on top of postgres of the latest version
FROM postgres

# this adds the createdb.sql file to the postgres server
ADD createdb.sql /docker-entrypoint-initdb.d

# declare the default postgres server port
EXPOSE 5432
