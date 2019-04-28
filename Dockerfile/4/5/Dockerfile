#version 0.0.1
FROM centos:7
RUN rpm -Uvh http://nginx.org/packages/centos/7/noarch/RPMS/nginx-release-centos-7-0.el7.ngx.noarch.rpm
RUN yum install -y nginx
RUN echo 'Hi,I am in your container buildByGiTHub' /usr/share/nginx/html/index.html/index
EXPOSE 80