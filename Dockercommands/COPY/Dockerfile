FROM almalinux:8
RUN yum install nginx:12.4 -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY qi /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]