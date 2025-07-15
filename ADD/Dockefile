FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html  
ADD https://raw.githubusercontent.com/obulanaidu/ansible/refs/heads/main/02-helloworld.yaml /usr/share/nginx/html/index.html  
CMD ["nginx", "-g", "daemon off;"]