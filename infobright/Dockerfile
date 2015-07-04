# dockers/infobright/Dockerfile

FROM centos:6.6

MAINTAINER rubicks

ADD \
  https://www.infobright.org/downloads/ice/infobright-4.0.7-0-x86_64-ice.rpm \
  infobright-4.0.7-0-x86_64-ice.rpm

RUN \
  yum -y update && \
  yum -y upgrade && \
  yum -y install sudo && \
  >>/etc/sudoers echo "Defaults !requiretty" && \
  yum -y localinstall infobright-4.0.7-0-x86_64-ice.rpm

# run \
#   yum -y update && \
#   yum -y upgrade

# /usr/local/infobright/postconfig.sh
# copy provision.sh provision.sh
# run /bin/bash provision.sh
# cmd /bin/bash
