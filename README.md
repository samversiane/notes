# NOTES
Some annotations about my adventures in tech world. 👨‍💻

## Working with Postgres and PgAdmin4 in docker (CLI)

### Postgres instance creating
- docker run -p 5432:5432 --name pg -e POSTGRES_PASSWORD=password postgres

### PgAdmin4 instance creating
- docker run -p 5555:80 --name pgadmin -e PGADMIN_DEFAULT_EMAIL="root@email.com" -e PGADMIN_DEFAULT_PASSWORD="password" dpage/pgadmin4

### Litle trick to run
- When creating a new server on PgAdmin4, in "connection -> host", must write the Gateway of Postgres instance, to find Gateway: docker inspect "Postgres instace name".
