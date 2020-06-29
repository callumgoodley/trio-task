# Derived from official mysql image (our base image)
FROM mysql/mysql-server:latest

# Add a database
COPY CreateTable.sql .
# Add the content of the .sql file to your image

ADD CreateTable.sql /docker-entrypoint-initdb.d

# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup

