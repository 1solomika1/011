FROM centos:latest

LABEL maintainer="hliantseva@gmail.com"
EXPOSE 8081
RUN yum update
CMD yum install -y apache; tail -f dev/null
