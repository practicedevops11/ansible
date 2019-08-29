FROM centos
MAINTAINER Elset
COPY nginx.repo /etc/yum.repos.d
RUN yum repolist
RUN yum install -y nginx
COPY index.html /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"] 

