FROM docker.elastic.co/kibana/kibana:6.4.3

# Replace config files
RUN rm -f /usr/share/kbana/config/kibana.yml
ADD config/ /usr/share/kibana/config/

EXPOSE 5601

