FROM almalinux:9
RUN dnf install nginx -y
COPY file.txt /usr/share/html/file.txt
CMD [ "nginx","-g","daemon off;" ]