# pgrouting_leveldb_docker

PostgreSQL_ROOT=/usr/pgsql-9.3/ cmake -H. -Bbuild

create database routing;
\c routing
CREATE EXTENSION postgis;
CREATE EXTENSION pgrouting;
SELECT * from pgr_version();

