FROM mysql:5.7.25

ENV MYSQL_ROOT_PASSWORD="devopspassword"
ENV MYSQL_DATABASE="accounts"
#dont expose passwords here
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
