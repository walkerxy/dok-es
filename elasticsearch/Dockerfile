FROM docker.elastic.co/elasticsearch/elasticsearch:7.9.3@sha256:9116cf5563a6360ed204cd59eb89049d7e2ac9171645dccdb1421b55dbae888b

RUN apt-get update \
	&& apt-get install -y vim

COPY --chown=elasticsearch:root elasticsearch.yml /usr/share/elasticsearch/config/