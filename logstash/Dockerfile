FROM docker.elastic.co/logstash/logstash:7.0.1@sha256:08ce6009987afdf3297330a8cc1a90b62062864d3fbe0edcd7adcf96f3613ef4

RUN rm -f /usr/share/logstash/pipeline/logstash.conf
COPY pipeline /usr/share/logstash/pipeline/
