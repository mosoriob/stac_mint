# STAC MINT

## Quickstart

1. Start services

```bash
$ docker-compose up -d
$ docker-compose run franklin migrate
```

2. Create a collection

```bash
$ curl -X POST -H "Content-Type: application/json" -d@examples/test_collection.json   localhost:9000/collections
```

3. List collection

```
$ curl http://localhost:9000/collections
```

