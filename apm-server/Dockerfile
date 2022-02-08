FROM docker.elastic.co/apm/apm-server:8.2.0-SNAPSHOT
COPY apm-server.yml /usr/share/apm-server/apm-server.yml
USER root
RUN chown root:root /usr/share/apm-server/apm-server.yml
RUN chmod go-w /usr/share/apm-server/apm-server.yml
USER apm-server
