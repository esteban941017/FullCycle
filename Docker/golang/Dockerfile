FROM golang:1.23

WORKDIR /usr/src/app

RUN go mod init hello.go && go mod tidy

COPY . .

ENTRYPOINT ["go", "run"]

CMD ["."]
