FROM nginx:1.14.1
COPY nginx.conf /etc/nginx
RUN mv /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf.disabled
EXPOSE 80
