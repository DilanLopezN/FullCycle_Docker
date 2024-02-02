
FROM golang:alpine AS builder

WORKDIR /app


COPY main.go .


RUN go mod init app


RUN go build -o app .


FROM scratch


COPY --from=builder /app/app /


CMD ["/app"]
