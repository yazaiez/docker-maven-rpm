FROM maven:3.6.2-jdk-12
MAINTAINER Yasser AZAIEZ <yaz@atolcd.com>

# Install Deps
RUN yum install rpm rpm-build  -y && \
    yum clean all && \
    rm -rf /var/cache/yum
