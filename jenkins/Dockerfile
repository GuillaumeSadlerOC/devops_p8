FROM jenkins/jenkins:lts
 
USER root
RUN apt-get update && apt-get install -y sudo
RUN echo "jenkins ALL=NOPASSWD: ALL" >> /etc/sudoers
 
USER jenkins