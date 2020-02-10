FROM nginx:1.17.6-alpine

WORKDIR /etc/nginx/

RUN apk update && apk add bash
RUN rm -rf /etc/nginx/conf.d/nginx.conf

COPY ./nginx.conf /etc/nginx/conf.d/ 