FROM node:24.4.0

WORKDIR /app

COPY . .

RUN npm i

COPY .env.sample .env

EXPOSE 8080

CMD ["npm","start"]
