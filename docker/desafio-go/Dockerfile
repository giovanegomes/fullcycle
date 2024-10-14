FROM golang AS builder

WORKDIR /src/app

COPY . .

RUN go build -ldflags "-s -w" /src/app/desafio.go
