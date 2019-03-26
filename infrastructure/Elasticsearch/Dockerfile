# Dockerfile for ELK stack
# Elasticsearch, Logstash, Kibana 6.6.1

# Build with:
# docker build -t <repo-user>/elk .

# Run with:
# docker run -p 5601:5601 -p 9200:9200 -p 5044:5044 -it --name elk <repo-user>/elk
# docker run -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" --name elasticsearch docker.elastic.co/elasticsearch/elasticsearch:6.7.0
FROM docker.elastic.co/elasticsearch/elasticsearch:6.7.0

# Install Google Cloud SDK
##RUN curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | apt-key add -
##RUN echo "deb http://packages.cloud.google.com/apt cloud-sdk-$(lsb_release -c -s) main" >> /etc/apt/sources.list.d/google-cloud-sdk.list
##RUN apt-get -yqq update
##RUN apt-get -yqq install google-cloud-sdk
##RUN apt-get clean
	
# WORKDIR /vsts

# COPY ./start.sh .
# RUN chmod +x start.sh

# CMD ["./start.sh"]
