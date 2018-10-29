FROM node:8-alpine

RUN set -xe \
    && apk add --no-cache bash git openssh

RUN npm install -g crmux

CMD crmux

