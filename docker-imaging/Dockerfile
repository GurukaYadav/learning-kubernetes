# FROM nginx
# COPY index.html /usr/share/nginx/html/index.html

#
# FROM centos:7
# RUN  yum install epel-release -y
# RUN  yum install nginx -y
# COPY index.html /usr/share/nginx/html/index.html
# EXPOSE 80
# ENTRYPOINT ["nginx", "-g", "daemon off;"]


FROM centos:7
# ENTRYPOINT ["ping","-c3","google.com"]
ENTRYPOINT ["ping","-c3"]
CMD ["google.com"]

