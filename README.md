# ElasticSearch Cluster for Local Development

Run your own ElasticSearch cluster with 1 master node, 2 slaves and Kibana for web administration.

### Getting started

1. Clone the repo
2. `docker-compose up`
3. Check the uptime and load of all the nodes within the cluster using a simple command like `curl -X GET "localhost:9200/_cat/nodes?v&pretty"`
4. Manage the cluster using Kibana, by visiting http://127.0.0.1:5601
