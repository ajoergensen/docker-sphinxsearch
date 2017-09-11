Sphinxsearch
============

> Sphinx is a fulltext F/OSS search engine that provides text search functionality to client applications.

### Usage

You must provide your own `sphinx.conf` as `/etc/sphinx/sphinx.conf`

 ```docker run -rm --name sphinxsearch -p 9306:9306 -p 9312:9312 -v $PWD/sphinx.conf:/etc/sphinx.conf:ro ajoergensen/sphinxsearch```

