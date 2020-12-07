# Search API Documentation 

The search service runs string match searches over the metadata store and returns matches in order by search fit. 


# Endpoints
 - **/{query}**


# /{query}

## GET

Searches the metadata store for literals matching the requested query. Search is based off Lucene 7.4 and supports all the same modifiers as Lucene .

```console
$ curl http://clarklab.uvarc.io/search/"test string"
```
