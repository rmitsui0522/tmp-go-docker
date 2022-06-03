FROM golang:1.17

# ホットリロードツール
RUN go install github.com/cosmtrek/air@v1.27.3

WORKDIR /app

CMD ["/app/start.sh"]
