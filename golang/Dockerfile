FROM golang:1.12.4
LABEL maintainer="Stefan Dillenburg <stefan.dillenburg@fit.fraunhofer.de>"

WORKDIR /go/src/app
COPY ./cross-compile ./

ENTRYPOINT ["cross-compile"]
