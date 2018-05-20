FROM alpine:3.7
MAINTAINER Tom Samstag @tecknicaltom

RUN apk upgrade --update \
 && apk add ruby \
 && gem install --no-document one_gadget \
 && rm -rf /root/src /tmp/* /var/cache/apk/*

ENTRYPOINT ["one_gadget"]
