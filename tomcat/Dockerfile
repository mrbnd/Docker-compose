FROM ubuntu:18.04
RUN apt-get update && apt install -y tomcat8
RUN mkdir -p /usr/share/tomcat8/conf && cp /etc/tomcat8/server.xml /usr/share/tomcat8/conf/server.xml && mkdir -p /usr/share/tomcat8/common/classes && mkdir -p /usr/share/tomcat8/server/classes && mkdir -p /usr/share/tomcat8/shared/classes && mkdir -p /usr/share/tomcat8/temp && mkdir -p /usr/share/tomcat8/logs
EXPOSE 8080
#CMD ["/usr/share/tomcat8/bin/catalina.sh", "run"]
CMD ["/bin/sh"]