FROM nginx:1.14.1
COPY nginx.conf /etc/nginx
COPY nginx-selfsigned.key /etc/ssl
COPY nginx-selfsigned.crt /etc/ssl/certs
COPY dhparam.pem /etc/ssl/certs
COPY ssl.conf /etc/nginx/conf.d
RUN mv /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf.disabled
EXPOSE 80
EXPOSE 443
