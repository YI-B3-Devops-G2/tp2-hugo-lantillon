FROM nginx:1.17.6-alpine

WORKDIR /etc/nginx/

RUN apk update && apk add bash

COPY nginx.conf /etc/nginx/conf.d/ 