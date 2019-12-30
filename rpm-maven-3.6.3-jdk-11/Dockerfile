FROM maven:3.6.3-jdk-11
MAINTAINER Yasser AZAIEZ <yaz@atolcd.com>

# Install Deps
RUN apt-get update && \
  apt-get install -y --force-yes rpm

# Cleaning
RUN apt-get clean
