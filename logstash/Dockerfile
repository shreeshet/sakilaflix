FROM docker.elastic.co/logstash/logstash:6.1.1

RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD ./config/logstash.conf /usr/share/logstash/pipeline/logstash.conf


