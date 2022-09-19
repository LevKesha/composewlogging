FROM nginx:stable-alpine

WORKDIR /nginx

#RUN chown nginx:nginx /nginx

USER root

COPY ./data /nginx/data
COPY ./conf /nginx/conf

CMD ["nginx", "-c", "/nginx/conf/nginx.conf"]