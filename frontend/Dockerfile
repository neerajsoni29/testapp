FROM centos:7
MAINTAINER NEERAJSONI2989@GMAIL.COM
RUN yum -y update
RUN yum -y install httpd
RUN useradd apachectl
#RUN mkdir/apps
#WORKDIR /apps
ADD code /var/www/html
ENV BACKENDLB=test
EXPOSE 80
CMD ["apachectl","-D","FOREGROUND"]