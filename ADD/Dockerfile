FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html 
ADD https://github.com/Jaiaws446/notes/blob/master/session-01.txt index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]