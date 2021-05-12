FROM ubuntu:latest

MAINTAINER Richard Chesterwood "contact@virtualpairprogrammers.com"

WORKDIR /usr/local/bin/

COPY test-program.jar .

RUN apt-get update && apt-get install -y openjdk-8-jdk

CMD ["java","-jar","test-program.jar"]
