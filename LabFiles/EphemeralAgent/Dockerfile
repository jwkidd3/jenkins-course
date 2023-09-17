FROM ubuntu
RUN apt-get update && apt-get install -y openssh-server openjdk-8-jdk maven git
RUN useradd jenkins --create-home && echo jenkins:jenkins | chpasswd 
RUN mkdir /var/run/sshd && /usr/sbin/sshd

