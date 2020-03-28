# elasticsearch-api-examples

To quickly start local elasticsearch cluster, use the following docker command.
	docker run -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:7.6.1
