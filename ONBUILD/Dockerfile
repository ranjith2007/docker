FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#This onbuild instruction runs only, when any user uses your image
ONBUILD COPY index.html /sr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]