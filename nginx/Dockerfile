FROM nginx:1.17.6-alpine

RUN apk update && apk add bash
RUN rm -fr /etc/nginx/conf.d/default.conf
COPY ./nginx/conf.d/nginx.conf /etc/nginx/conf.d
