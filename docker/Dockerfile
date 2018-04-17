FROM node:9.11-alpine

RUN apk add --no-cache openssh-client

VOLUME /usr/share/app
WORKDIR /usr/share/app

RUN npm install -g ionic@latest
