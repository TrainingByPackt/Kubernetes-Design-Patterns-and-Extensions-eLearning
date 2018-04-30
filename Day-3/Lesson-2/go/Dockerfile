FROM golang:1.9.5

ADD . /go/src/github.com/onuryilmaz/k8s-client-example/go/
WORKDIR /go/src/github.com/onuryilmaz/k8s-client-example/go/

RUN go build -v -o client

CMD ["/go/src/github.com/onuryilmaz/k8s-client-example/go/client"]

