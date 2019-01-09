FROM alpine:latest 
RUN apk add --update
RUN apk add --no-cache nginx

# forward request and error logs to docker log collector
RUN ln -sf /dev/stdout /var/log/nginx/access.log \
&& ln -sf /dev/stderr /var/log/nginx/error.log

#https://github.com/nginxinc/docker-nginx/blob/master/stable/alpine/Dockerfile


