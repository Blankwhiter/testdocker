FROM anapsix/alpine-java:8_server-jre_unlimited
MAINTAINER belonghuang<belonghuang@126.com>

RUN apt-get -y install vim
RUN apt-get -y install net-tools
RUN apt-get -y install lsof

RUN mkdir -p /jar/
WORKDIR /jar/
EXPOSE 8077

ADD ./jar/zookeeper-admin-java.jar ./zookeeper-admin-java.jar

CMD java -Djava.security.egd=file:/dev/./urandom -jar zookeeper-admin-java.jar  

CMD echo "success========================OK"