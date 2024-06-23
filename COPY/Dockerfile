FROM almalinux:9
RUN install nginx -y
COPY file.txt /usr/share/html/file.txt
CMD [ "nginx","-g","daemon off;" ]