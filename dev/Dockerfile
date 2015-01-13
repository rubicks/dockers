FROM ubuntu:latest
MAINTAINER rubicks

RUN apt-get -qq update       && \
    apt-get -qq dist-upgrade && \
    apt-get -qq install \
        autoconf        \
        automake        \
        git             \
        libtool         \
        libz-dev        \
        make            \
        zlib1g-dev

CMD /bin/bash
