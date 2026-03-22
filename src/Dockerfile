# For deployment on railway.app
FROM golang:latest

WORKDIR /

COPY . .

RUN go build go.mod

CMD [ "npm run start" ]
