# dockers/dev/Dockerfile

FROM ubuntu:latest
MAINTAINER rubicks

RUN apt-get -y update       && \
    apt-get -y dist-upgrade && \
    apt-get -y install   \
        autoconf         \
        autoconf-archive \
        automake         \
        g++              \
        git              \
        libtool          \
        libz-dev         \
        make

CMD /bin/bash
