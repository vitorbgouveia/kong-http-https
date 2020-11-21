FROM kong:latest

COPY kong.conf /etc/kong/kong.conf
RUN mkdir -p /usr/local/kong/plugins

USER root
RUN chown -R kong:root /usr/local/*

USER kong