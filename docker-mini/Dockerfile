FROM debian:jessie
MAINTAINER Toomore Chiang <toomore0929@gmail.com>

RUN apt-get update && apt-get install -y ca-certificates && \
    rm -rf /var/lib/apt/lists/*

ADD ./plivoSendMass /usr/local/bin/
ADD ./plivoQuickSend /usr/local/bin/
