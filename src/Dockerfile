# For deployment on railway.app
FROM golang:latest

WORKDIR /

COPY . .

RUN go build

CMD [ "npm run start" ]
