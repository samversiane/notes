# NOTES
Some annotations about my adventures in tech world.

##Working with Postgres and PgAdmin4 in docker (cli)

###Postgres instance creating
- docker run -p 5432:5432 --name pg -e POSTGRES_PASSWORD=password postgres

###PgAdmin4 instance creating
- docker run -p 5432:5432 --name pg -e POSTGRES_PASSWORD=password postgres

###Litle trick to run
- When creating a new server on PgAdmin4, in connection -> host, must write the IPAddress of Postgres instance, to find IPAddres: docker inspect "instace name of Postgres".
