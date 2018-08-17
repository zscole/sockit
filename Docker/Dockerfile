FROM ubuntu:latest

ENV HOME /root

RUN apt-get update && apt-get upgrade && apt-get install --yes --quiet \
    apt-utils \
    curl \
    git \
    mercurial \
    golang-go

RUN go get github.com/gorilla/websocket

WORKDIR /srv/

ENTRYPOINT /bin/bash

