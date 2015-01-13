# dockers/mingw/Dockerfile

FROM rubicks/xdev
MAINTAINER rubicks

RUN dpkg --add-architecture i386 && \
    apt-get -qq update           && \
    apt-get -qq dist-upgrade     && \
    apt-get -qq install  \
        mingw32          \
        mingw32-binutils \
        mingw32-runtime  \
        wine

CMD /bin/bash
