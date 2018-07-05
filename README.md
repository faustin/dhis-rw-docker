## Rwanda SPH SMT DHIS2

- docker-compose
- docker images
- docker exec -it <imageId> bash
- su postgres
- psql dhis
- drop database dhis
- create database dhis
- GRANT ALL PRIVILEGES ON DATABASE dhis TO dhis
- GRANT postgres TO dhis
- \q
- exit
- cat smt-dhis.sql  | psql dhis

