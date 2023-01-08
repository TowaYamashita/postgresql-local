# postgresql-local

|||
|:--|:--|
|postgresql|14|
|port(local side)|54321|
|port(container side)|5432|

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
