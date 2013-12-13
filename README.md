# Dockerfile PgRest

## Info

This Dockerfile creates a container running pgrest.

https://github.com/clkao/pgrest

Here's what it does in particular:

- building Postgresql using [dockyard](https://github.com/dynport/dockyard)
- exposing it on port `5432`
- initializes a database in `/var/lib/postgresql/9.2/main`
- inserts a superuser in the database: `docker:d0cker` (change in the Dockerfile)


## Install



## Meta

Build with docker version `0.5.1`

## Reference

https://wiki.postgresql.org/wiki/Apt
