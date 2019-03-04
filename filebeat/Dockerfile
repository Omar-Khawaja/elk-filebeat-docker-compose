FROM docker.elastic.co/beats/filebeat:6.6.1

RUN echo "initial testing of log file" >> /usr/share/filebeat/logs/testlog.log

COPY ./filebeat.yml /usr/share/filebeat/filebeat.yml
