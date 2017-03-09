FROM centos:6

RUN yum update -y && yum install -y epel-release && yum install -y nginx

RUN cd /opt && curl -O http://apache.claz.org/zookeeper/zookeeper-3.4.6/zookeeper-3.4.6.tar.gz && tar zxvf zookeeper-3.4.6.tar.gz && rm -rf /opt/zookeeper-3.4.6.tar.gz && mv /opt/zookeeper-3.4.6 /opt/zookeeper


COPY gatekeeper /gatekeeper
