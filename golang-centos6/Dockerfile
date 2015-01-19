FROM centos:centos6
MAINTAINER Prima Adi <prima101112@gmail.com>

RUN yum install -y wget git nano 
RUN yum install -y http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm

RUN yum install -y mongodb-server
RUN yum install -y golang

RUN mkdir /go
ENV GOPATH  /go
