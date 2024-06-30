---
title: "PostgreSQL"
wight: 1
---

# PostgreSQL

## Login

```bash
psql -U <username> -h <host> -p 5432 -W -d <database_name>
```

## List all database

```sql
\l
```

## Connect to database

```sql
\c database_name
```

## List tables

```sql
\dt
```

## Dump all database

```bash
pg_dumpall -U <username> -h <host> -p 5432 -W -f ./dir/postgre.sql
```

## Dump single database

```bash
pg_dump -U <username> -h <host> -p 5432 -W -d <database_name> > ./dir/database_name.sql
```



### reference
https://www.postgresqltutorial.com/postgresql-cheat-sheet/