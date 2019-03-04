FROM logstash:6.6.1

RUN bin/logstash-plugin install logstash-input-beats

COPY ./logstash.yml /usr/share/logstash/config/logstash.yml

COPY ./logstash.conf /usr/share/logstash/pipeline/logstash.conf
