FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/htmp/index.html
COPY index.html /usr/share/nginx/htmp/index.html
CMD [ "nginx", "-g", "daemon off;" ]