FROM postgres:14.1-alpine

ENV 	POSTGRES_DB=db \
	POSTGRES_USER=usr \
   	POSTGRES_PASSWORD=pwd

COPY sqlfiles/01-CreateScheme.sql /docker-entrypoint-initdb.d/
COPY sqlfiles/02-InsertData.sql /docker-entrypoint-initdb.d/
