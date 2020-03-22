FROM ubuntu:16.04

LABEL MAINTAINER="Habeeb Odunsi <habeebodunsi@yahoo.com>"

RUN apt-get update && \
    apt-get install -y \
    bmon \
    curl \
    dnsutils \
    iftop \
    iperf \
    iputils-ping \
    lynx \
    mtr-tiny \
    net-tools \
    netcat \
    nmap \
    openssh-client \
    strace \
    sysstat \
    tcpdump \
    tcptraceroute \
    traceroute \
    telnet \
    vim \
    wget \
    iproute \
    iperf \
    && apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
