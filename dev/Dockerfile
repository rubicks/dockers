# dockers/dev/Dockerfile

FROM ubuntu:latest
MAINTAINER rubicks

RUN apt-get -qq update       && \
    apt-get -qq dist-upgrade && \
    apt-get -qq install  \
        autoconf         \
        autoconf-archive \
        automake         \
        git              \
        libtool          \
        libz-dev         \
        make

CMD /bin/bash
