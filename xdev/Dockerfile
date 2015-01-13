# dockers/xdev/Dockerfile

FROM rubicks/dev
MAINTAINER rubicks

RUN apt-get -qq update       && \
    apt-get -qq dist-upgrade && \
    apt-get -qq install    \
        libX11-dev         \
        libfltk1.3-dev     \
        libfontconfig1-dev \
        libglu1-mesa-dev   \
        libice-dev         \
        libjpeg-dev        \
        libjpeg62-dev      \
        libpng-dev         \
        libpng12-dev       \
        libx11-dev         \
        libxcursor-dev     \
        libxext-dev        \
        libxft-dev         \
        libxi-dev          \
        libxinerama-dev    \
        libxrender-dev     \
        mesa-common-dev

CMD /bin/bash
