FROM node:22-alpine3.19

LABEL maintainer="v0.1"

RUN mkdir /var/node

WORKDIR /var/node

COPY app.js .

EXPOSE 3000

ARG VERSION
ENV VERSION=${VERSION:-1.0.0}

CMD [ "node", "app.js" ]