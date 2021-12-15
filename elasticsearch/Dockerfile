ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELK_VERSION}

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-nori
RUN elasticsearch-plugin install analysis-nori
RUN elasticsearch-plugin install -b https://d3g5vo6xdbdb9a.cloudfront.net/downloads/elasticsearch-plugins/opendistro-alerting/opendistro-alerting-1.13.1.0.zip
