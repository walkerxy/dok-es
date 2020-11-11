FROM docker.elastic.co/kibana/kibana:7.9.3@sha256:75b917df52179cc29efbfe88159efbb186fd8697835b0849fde22f25ac74ac3b

RUN apt-get update \
	&& apt-get install -y vim
	
COPY --chown=kibana:root elasticsearch.yml /usr/share/kibana/config/