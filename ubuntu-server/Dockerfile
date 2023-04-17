FROM ubuntu:22.10
RUN apt-get update
RUN apt-get install -y openssh-server
RUN apt install -y iproute2
RUN apt-get clean 
RUN apt clean
CMD ["/usr/sbin/sshd", "-D"]
