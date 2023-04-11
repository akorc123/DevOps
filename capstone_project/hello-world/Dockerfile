FROM node:alpine

WORKDIR /app
RUN apk update && apk add ansible

COPY . .

CMD ["npm", "start"]

