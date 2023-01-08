# postgresql-local

|||
|:--|:--|
|postgresql|14|
|port|5432|

|||
|:--|:--|
|database name|localdb|
|user ID|postgres|
|password|postgres|

# Usage

## launch

```
docker-compose up -d
```

## connect this container
```
docker exec -it postgres /bin/sh
psql -h localhost -U postgres
```
