FROM almalinux:8
LABEL AUTHOR="Narayana"
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY qi /usr/share/nginx/html/ 
