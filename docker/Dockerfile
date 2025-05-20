FROM amazonlinux:2

RUN yum update -y && \
    yum install -y nginx && \
    yum clean all

COPY index.html /usr/share/nginx/html/index.html
COPY start.sh /start.sh

RUN chmod +x /start.sh

CMD ["/start.sh"]
