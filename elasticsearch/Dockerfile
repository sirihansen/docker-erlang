FROM docker.elastic.co/elasticsearch/elasticsearch:6.4.3

# Replace config files
RUN rm -f /usr/share/elasticsearch/config/elasticsearch.yml
ADD config/ /usr/share/elasticsearch/config/

EXPOSE 9200
EXPOSE 9300

