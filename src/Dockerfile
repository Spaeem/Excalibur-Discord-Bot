# For deployment on railway.app
FROM golang:latest

WORKDIR /

COPY . .

RUN go build Excalibur

CMD [ "npm run start" ]
