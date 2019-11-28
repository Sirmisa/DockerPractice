FROM ubuntu:latest

MAINTAINER "Panchito"

RUN apt-get update && apt-get install -y openjdk-8-jdk

WORKDIR /usr/local/bin

COPY Hola.jar .

CMD ["java", "jar", "Hola.jar"]
