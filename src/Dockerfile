# For deployment on railway.app
FROM golang:latest

WORKDIR /

COPY . .

RUN go build main.go

CMD [ "npm run start" ]
