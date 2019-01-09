FROM alpine:latest

ENV MYSQL_ROOT_PASSWORD root
ENV MYSQL_DATABASE app
ENV MYSQL_USER user
ENV MYSQL_PASSWORD password


RUN apk add --update
RUN test -z "$VER" || apk add --no-cache mysql $VER && apk add --no-cache mysql
VOLUME [ "/var/lib/mysql" ]
ENTRYPOINT ["mysql"]
