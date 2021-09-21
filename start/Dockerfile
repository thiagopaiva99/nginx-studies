FROM nginx:alpine

EXPOSE 8080

RUN chmod -R 755 /usr/share/nginx && \
    chown nginx:nginx  /usr/share/nginx/html/* && \
    chmod -R 755 /etc/nginx/conf.d/default.conf

CMD nginx -g 'daemon off;'
