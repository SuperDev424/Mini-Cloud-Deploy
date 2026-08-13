FROM golang:1.27rc1

RUN mkdir /app
WORKDIR /app

ADD . /app
RUN go install ./...

CMD /go/bin/greeter_server
