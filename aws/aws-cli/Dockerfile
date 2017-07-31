FROM alpine:latest

MAINTAINER AND Digital <hello@and.digital>

RUN apk add --update --quiet python py-pip groff && \
    pip --upgrade install awscli && \
    rm -rf /var/cache/*
