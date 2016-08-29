FROM logstash:2.3.4-1
MAINTAINER Elliot
#ENV LOGSTASH_HOME /opt/logstash
WORKDIR ${LOGSTASH_HOME}
RUN bin/logstash-plugin install logstash-input-beats
