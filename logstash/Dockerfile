FROM docker.elastic.co/logstash/logstash:7.7.0

LABEL maintainer="ermu0420@gmail.com"

COPY ./config /usr/share/logstash/config
COPY ./pipeline /usr/share/logstash/pipeline

USER root

RUN echo "Asia/Shanghai" > /etc/timezone

USER logstash