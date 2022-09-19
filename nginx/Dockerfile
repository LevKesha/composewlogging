FROM nginx:stable-alpine

WORKDIR /nginx

RUN chown nginx:nginx /nginx

USER nginx

COPY ./data /usr/share/nginx/html
COPY ./nginx.conf /etc/nginx/nginx.conf

CMD ["nginx", "-c", "/nginx/conf/nginx.conf"]