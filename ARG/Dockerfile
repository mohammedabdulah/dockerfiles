FROM almalinux:8
RUN yum install nginx -y  
CMD ["ping", "google.com"]
ARG username
RUN adduser ${username}
USER ${username}
