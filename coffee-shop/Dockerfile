#FROM sdaschner/open-liberty:javaee8-tracing-jdk8-b3

FROM docker.io/open-liberty:19.0.0.9-javaee8-java8-openj9

COPY openliberty/server.xml $CONFIG_DIR

COPY target/coffee-shop.war $DEPLOYMENT_DIR
