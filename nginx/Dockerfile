FROM nginx:stable-alpine

WORKDIR /nginx

RUN chown nginx:nginx /nginx

USER nginx

COPY ./data /nginx/data
COPY ./nginx.conf /nginx/conf

CMD ["nginx", "-c", "/nginx/conf/nginx.conf"]