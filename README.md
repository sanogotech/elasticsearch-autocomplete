# SpringBoot Application with AutoComplete feature with ElasticSearch

## Docs
- https://medium.com/@milosbiljanovic/springboot-autocomplete-with-elasticsearch-11ea95d58854


##  config/elasticseach.yml

cluster.name: clusterarchitech
discovery.zen.ping.unicast.hosts: ["localhost:9300"]

##  Tests

- curl localhost:8080/users/search?keywords=bel%20bahamas
