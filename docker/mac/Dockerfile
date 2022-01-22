FROM node:16.13.2-alpine3.15

ENV LANG=C.UTF-8 \
    TZ=Asia/Tokyo \
    HOST=0.0.0.0 \
    NPM_CONFIG_PRODUCTION=false

RUN apk add --no-cache --virtual .gyp python3 make g++
