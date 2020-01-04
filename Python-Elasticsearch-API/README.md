# Elasticsearch Python API
- This is the low level API, not the search (elasticsearch-dsl)
- Main use case is automating health checks and other low level functions
- There is some basic search but not a lot  
API link _https://elasticsearch-py.readthedocs.io/en/master/api.html_

## Setup
- Run the [Star Wars Setup](https://github.com/macatak/ELK/blob/master/Python-Elasticsearch-API/ElasticsearchLoadStarWars.ipynb) notebook. This will setup a few indices using the Star Wars API. Most of the examples use one of those indices  
- If you don't want to see all the print statements comment them out. The notebook has them all included so it's a good example of what you should see. It's a little verbose but I like seeing an indication something is happening  
- I use VirtualBox and run the stack on a VM. I do not use localhost but run Elasticsearch on an IP

## Index API
- Contans basic index operations
- open, close, create, delete, check exists, flush, force merge, refresh, shard store info, segment info, shrink (in progress), operations status.  



This IS still a work in progress
