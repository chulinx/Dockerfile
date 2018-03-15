FROM hub.c.163.com/public/centos:6.7
RUN yum clean all \
    && yum remove openssh-server -y\
    && yum install openssh-server vim net-tools passwd -y
EXPOSE 22
CMD ["/usr/sbin/sshd","-D"]
