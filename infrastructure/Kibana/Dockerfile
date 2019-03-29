# Dockerfile for ELK stack
# Elasticsearch, Logstash, Kibana 6.6.1

# Build with:
# docker build -t <repo-user>/elk .

# Run with:
# docker run -p 5601:5601 -p 9200:9200 -p 5044:5044 -it --name elk <repo-user>/elk
# docker run --link elasticsearch:elasticsearch -p 5601:5601 --name kibana docker.elastic.co/kibana/kibana:6.7.0
FROM docker.elastic.co/kibana/kibana:6.7.0
#FROM docker.elastic.co/kibana/kibana:6.5.1

RUN apt-get -yqq update && apt-get -yqq upgrade
## gcloud builds submit --config cloudbuild.yaml .

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
