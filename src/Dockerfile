# For deployment on railway.app
FROM golang:latest

WORKDIR /

COPY . .

RUN go build Excalibur-Discord-Bot

CMD [ "npm run start" ]
