# commands 

> script backup
> - docker exec postgres pg_dump -U postgres dbname > backup.sql

> script recovery backup
docker exec -i postgres psql -U postgres -d dbname < backup.sql

> script recovery backup with pg_restore
> - docker exec -it postgres pg_restore -U postgres -v -d dbname < //home/nameuser/db_copy/bakup00.pgdump

> script 
> - pg_restore -U postgres -d dbname < backup.pgdump

> start psql
> - docker exec -it postgres psql -U postgres

> create role
> - CREATE ROLE rolename;

> permissions role
> - GRANT ALL ON DATABASE dbname TO rolename;

> create container rabbitmq
> - docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management
