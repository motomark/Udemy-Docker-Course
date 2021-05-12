FROM openjdk:8u131-jdk-alpine

MAINTAINER Richard Chesterwood "contact@virtualpairprogrammers.com"

WORKDIR /usr/local/bin/

COPY fleetman-0.0.1-SNAPSHOT.war webapp.war


CMD ["java", "-Dspring.profiles.active=docker-demo", "-jar", "webapp.war"]