FROM mysql:5.7.23
RUN /bin/bash -c "/usr/bin/mysqld_safe --skip-grant-tables &" && \
  sleep 5 && \
  mysql -u root -e "CREATE DATABASE ocrdev"
