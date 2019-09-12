FROM node:alpine

LABEL MAINTAINER "OTA2000 <yasuhiroota26@gmail.com>"

RUN npm install -g @google/clasp

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
VOLUME /usr/src/app

ENTRYPOINT ["clasp"]
CMD ["--help"]
