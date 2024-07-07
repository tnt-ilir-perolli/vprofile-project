FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Ilir"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"
VOLUME ["/var/lib/mysql"]
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql