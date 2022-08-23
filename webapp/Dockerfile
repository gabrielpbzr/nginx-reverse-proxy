FROM golang:1.19-alpine AS build
WORKDIR /build
COPY main.go .
COPY go.mod .
RUN GOOS=linux go build

FROM alpine:3.16

COPY --from=build /build/helloapp /usr/app/my-app

EXPOSE 8080

ENTRYPOINT ["/usr/app/my-app"]
