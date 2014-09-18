FROM ubuntu:latest

MAINTAINER Johnathan David Froeming <johnathan@kodokuman.com>

RUN echo "deb http://br.archive.ubuntu.com/ubuntu/ trusty main restricted\n \
deb-src http://br.archive.ubuntu.com/ubuntu/ trusty main restricted\n \
deb http://br.archive.ubuntu.com/ubuntu/ trusty-updates main restricted\n \
deb-src http://br.archive.ubuntu.com/ubuntu/ trusty-updates main restricted\n \
deb http://br.archive.ubuntu.com/ubuntu/ trusty universe\n \
deb-src http://br.archive.ubuntu.com/ubuntu/ trusty universe\n \
deb http://br.archive.ubuntu.com/ubuntu/ trusty-updates universe\n \
deb-src http://br.archive.ubuntu.com/ubuntu/ trusty-updates universe\n \
deb http://br.archive.ubuntu.com/ubuntu/ trusty-security main restricted\n \
deb-src http://br.archive.ubuntu.com/ubuntu/ trusty-security main restricted\n \
deb http://br.archive.ubuntu.com/ubuntu/ trusty-security universe\n \
deb-src http://br.archive.ubuntu.com/ubuntu/ trusty-security universe\n " > /etc/apt/sources.list


RUN apt-get update && \
    apt-get upgrade -y
