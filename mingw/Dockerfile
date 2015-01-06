FROM rubicks/dev
MAINTAINER rubicks

RUN dpkg --add-architecture i386
RUN apt-get -qq update
RUN apt-get -qq dist-upgrade
RUN apt-get -qq install mingw32 mingw32-binutils mingw32-runtime wine

