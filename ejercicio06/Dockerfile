FROM registry.access.redhat.com/redhat-openjdk-18/openjdk18-openshift:1.12-1.1655301789
ARG JAR_FILE
COPY ${JAR_FILE} /deployments
EXPOSE 8080
USER 185