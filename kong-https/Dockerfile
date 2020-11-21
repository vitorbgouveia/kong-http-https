FROM kong:latest

ADD ./certs /etc/kong/certs
COPY kong.conf /etc/kong/kong.conf
RUN mkdir -p /usr/local/kong/plugins

USER root
RUN chown -R kong:root /etc/kong/certs
RUN chown -R kong:root /usr/local/*

USER kong
