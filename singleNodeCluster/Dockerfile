# Base Image
FROM ubuntu:20.04

LABEL name="ehdrn3020"
LABEL version="1.0"

# Set ENV
ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64
ENV HADOOP_VERSION 3.3.2
ENV HADOOP_URL https://dlcdn.apache.org/hadoop/common/hadoop-$HADOOP_VERSION/hadoop-$HADOOP_VERSION.tar.gz

RUN apt-get update && \
    apt-get install -y ssh \
    apt-get install -y pdsh \
    apt-get install -y curl \
    apt-get install -y openjdk-8-jdk