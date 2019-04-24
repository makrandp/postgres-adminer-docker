# PostgreSql with Docker

### Adminer is used for managing the database

## Setup 
```$xslt
mkdir ~/postgres-data #persistent data
docker-compose up
```

* adminer: http://localhost:8080

### Adminer Setup
- System: `PostgreSQL`
- Server: `postgres-dev`
- Username: `dev`
- Password: `password`
- Database: `demodb` 

## Useful Commands
```$xslt
docker-compose up
docker-compose rm -f
docker-compose down --rmi all
```
