FROM golang:1.17 AS builder

WORKDIR /go/src/app

COPY . .

RUN go mod init && \
    go build math.go

CMD ["./math"]