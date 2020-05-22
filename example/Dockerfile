FROM alpine:latest

LABEL maintainer="johndoe@gmail.com"

RUN apk add --update npm

COPY . /src

WORKDIR /src

RUN npm install

EXPOSE 8080

ENTRYPOINT ["node", "./app.js"]