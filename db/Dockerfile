FROM mysql:5.7

COPY schema.sql /schema.sql

EXPOSE 3306

CMD ["mysqld","--init-file=/schema.sql"]
