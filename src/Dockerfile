# For deployment on railway.app
FROM golang:latest

WORKDIR /

COPY . .

RUN go build src

CMD [ "npm run start" ]
