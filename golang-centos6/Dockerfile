FROM centos:centos6
MAINTAINER Prima Adi <prima101112@gmail.com>

RUN yum install -y wget git nano 
RUN yum install -y http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm

RUN yum install -y mongodb-server-2.4.12-2
RUN yum install -y golang-1.3.3-1

RUN mkdir /go
ENV GOPATH  /go
