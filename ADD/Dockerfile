FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/nikich8/ansible/main/01-playbook.yaml /tmp/
CMD ["nginx", "-g","daemon off;"]