FROM golang:1.11
WORKDIR /go/src/github.com/windmilleng/integration/oneup
ADD . .
RUN go install github.com/windmilleng/integration/oneup
ENTRYPOINT /go/bin/oneup