FROM node:8-alpine

RUN apk update && apk add git

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

RUN git clone https://github.com/jishi/node-sonos-web-controller.git .
RUN npm install

ADD favicon.ico /usr/src/app/static

EXPOSE 8080
CMD [ "node", "server.js" ]
