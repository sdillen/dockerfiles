FROM node:13.10.1
LABEL maintainer="Stefan Dillenburg"

COPY entrypoint.sh /usr/local/bin/entrypoint

RUN mkdir /usr/src/app

ENTRYPOINT [ "entrypoint" ]
