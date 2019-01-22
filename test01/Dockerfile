FROM centos
MAINTAINER belonghuang<belonghuang@126.com>

ENV MYPATH /usr/local
WORKDIR $MYPATH

RUN yum -y install vim
RUN yum -y install net-tools

EXPOSE 8080

CMD echo $MYPATH 
CMD echo "success========================OK"
CMD /bin/bash
