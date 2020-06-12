FROM ubuntu:18.04
RUN apt-get update && apt install -y default-jdk maven git
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
WORKDIR "/boxfuse-sample-java-war-hello"
RUN  mvn package
CMD ["/bin/bash"]