FROM almalinux:9
RUN dnf install nginx -y
ADD https://github.com/daws-81s/notes/blob/main/session-42.txt /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]