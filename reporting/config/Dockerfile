FROM alpine:3.23.2

COPY ./services /config
COPY ./init.sh /init.sh

RUN apk add --update curl && rm -rf /var/cache/apk/*

CMD /bin/true