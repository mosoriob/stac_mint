# STAC MINT


Start services

```bash
$ docker-compose up -d
$ docker-compose run franklin migrate
```

Create a collection

```bash
$ curl -X POST -H "Content-Type: application/json" -d '{"stac_version": "0.9.0", "stac_extensions": [], "id": "test-collection2", "title":   null, "description": "Example collection to post to API", "keywords": [], "license": "proprietary", "providers": [], "extent":             {"spatial": {"bbox": [[13.330610521659846, 52.363530645448044, 13.756192207996433, 52.64467528345354]]}, "temporal": {"interval": [["2018- 03-03T10:20:19Z", "2018-03-03T10:20:19Z"]]}}, "summaries": {}, "properties": {}, "links": []}'
```
