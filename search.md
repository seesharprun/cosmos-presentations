# Search Queries

Base Query:

```
https://[account].search.windows.net/indexes/[index]/docs?api-version=2016-09-01&search=*
```

Paged Query with Count:

```
https://[account].search.windows.net/indexes/[index]/docs?api-version=2016-09-01&search=*&$count=true&$top=5&$skip=20
```

Filtered Query:

```
https://[account].search.windows.net/indexes/[index]/docs?api-version=2016-09-01&search=bachelor
```

Query with Facets:

```
https://[account].search.windows.net/indexes/[index]/docs?api-version=2016-09-01&search=*&facet=BedroomCount
```


Query with Filtering:

```
https://[account].search.windows.net/indexes/[index]/docs?api-version=2016-09-01&search=*&$filter=BedroomCount eq 3
```
