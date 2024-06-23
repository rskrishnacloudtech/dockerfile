FROM almalinux:9
RUN dnf install nginx -y
COPY file.txt /usr/share/nginx/html/file.txt
CMD [ "nginx","-g","daemon off;" ]