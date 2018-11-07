FROM docker.io/openjdk:8-jre

MAINTAINER Hygieia@capitalone.com

RUN mkdir /hygieia 

COPY deploymnets/*.jar /hygieia

WORKDIR /hygieia

VOLUME ["/hygieia/logs"]

CMD java -jar jenkins-build-collector*.jar 

