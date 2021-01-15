FROM docker.elastic.co/beats/metricbeat:8.0.0-SNAPSHOT
COPY metricbeat.yml /usr/share/metricbeat/metricbeat.yml
USER root
RUN chown root:root /usr/share/metricbeat/metricbeat.yml
RUN metricbeat modules disable elasticsearch kibana
USER metricbeat
