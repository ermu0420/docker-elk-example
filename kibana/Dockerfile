FROM docker.elastic.co/kibana/kibana:7.7.0

LABEL maintainer="ermu0420@gmail.com"

COPY ./config/kibana.yml /usr/share/kibana/config/kibana.yml

USER root

RUN echo "Asia/Shanghai" > /etc/timezone

USER kibana
