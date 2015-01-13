FROM ubuntu:latest
MAINTAINER rubicks

RUN apt-get -qq update
RUN apt-get -qq dist-upgrade
RUN apt-get -qq install make autoconf automake libtool git
RUN apt-get -qq install libz-dev zlib1g-dev
CMD /bin/bash
