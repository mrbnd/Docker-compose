FROM alpine:latest
RUN apk add openjdk8 && wget http://mirror.linux-ia64.org/apache/tomcat/tomcat-8/v8.5.56/bin/apache-tomcat-8.5.56.tar.gz && tar xvzf apache-tomcat-8.5.56.tar.gz
EXPOSE 8080
CMD ["/apache-tomcat-8.5.56/bin/catalina.sh", "run"]


