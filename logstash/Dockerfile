FROM logstash:latest

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json 

RUN logstash-plugin install logstash-input-azurewadtable
RUN logstash-plugin install logstash-output-applicationinsights