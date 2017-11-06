FROM golang:1.8
MAINTAINER Christophe Osuna christophe@osuna.pro

# go-dep
ADD https://github.com/golang/dep/releases/download/v0.3.2/dep-linux-amd64 /go/bin/dep
RUN chmod +x /go/bin/dep

# go-bindata
RUN go get -u github.com/jteeuwen/go-bindata/...
