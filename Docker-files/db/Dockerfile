FROM mysql:8.0.33
LABEL "project"="Kubernetes-project"
LABEL "Author"="Riya"

ENV MYSQL_ROOT_PASSWORD="dbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql