ARG STACK_VERSION

FROM docker.elastic.co/beats/metricbeat:${STACK_VERSION}

COPY metricbeat.yml /usr/share/metricbeat/metricbeat.yml

USER root
RUN chown root /usr/share/metricbeat/metricbeat.yml