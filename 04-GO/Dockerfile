FROM golang:1.21.10

COPY src /go/src

RUN go build -o bin/sample src/main.go

EXPOSE 80

CMD ["/go/bin/sample"]
