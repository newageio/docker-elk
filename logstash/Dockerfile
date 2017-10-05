# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.6.1

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-kafka
RUN logstash-plugin install logstash-codec-avro_schema_registry
