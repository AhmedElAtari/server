FROM frolvlad/alpine-glibc:glibc-2.28
WORKDIR /app
RUN apk add --no-cache ca-certificates tzdata
EXPOSE 80
ENTRYPOINT ["/app"]

FROM golang:1.14.2-stretch

ENV CGO_ENABLED=1
ENV GOOS=linux
ENV GOARCH=amd64
