FROM centos:7
RUN yum install -y java
RUN mkdir /opt/tomcat
ADD https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.70/bin/apache-tomcat-9.0.70.tar.gz /opt/tomcat
WORKDIR /opt/tomcat
RUN tar -xvf apache-tomcat-9.0.70.tar.gz && mv apache-tomcat-9.0.70/* /opt/tomcat/
RUN rm -rf apache-tomcat-9.0.70.tar.gz && rmdir apache-tomcat-9.0.70/
