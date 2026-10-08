# Quête 1 - Découverte de Docker

## SELECT * FROM products;

```
 id |     name     | price_cents
----+--------------+-------------
  1 | Sticker Demo |         150
(1 row)
```

## \dt

```
         List of relations
 Schema |   Name   | Type  | Owner
--------+----------+-------+-------
 public | products | table | demo
(1 row)
```

## docker logs --tail 3 demo-db

```
2026-10-08 05:41:32.794 UTC [1] LOG:  listening on Unix socket "/var/run/postgresql/.s.PGSQL.5432"
2026-10-08 05:41:32.800 UTC [57] LOG:  database system was shut down at 2026-10-08 05:41:32 UTC
2026-10-08 05:41:32.807 UTC [1] LOG:  database system is ready to accept connections
```
