FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
COPY qi/ /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]
