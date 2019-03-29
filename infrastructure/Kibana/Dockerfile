# Dockerfile for ELK stack
# Elasticsearch, Logstash, Kibana 6.6.1

# Run with:
# docker run --link elasticsearch:elasticsearch -p 5601:5601 --name kibana docker.elastic.co/kibana/kibana:6.7.0
FROM docker.elastic.co/kibana/kibana:6.7.0

RUN apt-get -y update
RUN apt-get -y upgrade
