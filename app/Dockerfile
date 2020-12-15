FROM golang

RUN mkdir /src

WORKDIR /src

ADD . .

RUN go build -o app .

EXPOSE 5555

ENTRYPOINT [ "./app" ]
