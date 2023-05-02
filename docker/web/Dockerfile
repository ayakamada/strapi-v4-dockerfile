FROM node:16-alpine

RUN mkdir /srv/web && chown 1000:1000 -R /srv/web


WORKDIR /srv/web

VOLUME /srv/web


CMD ["yarn", "dev"]