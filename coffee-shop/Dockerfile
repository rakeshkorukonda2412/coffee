#FROM sdaschner/open-liberty:javaee8-tracing-jdk8-b3

FROM docker.io/amd64/open-liberty:21.0.0.12-kernel-slim-java8-openj9

COPY openliberty/server.xml $CONFIG_DIR

COPY target/coffee-shop.war $DEPLOYMENT_DIR
