FROM node:latest

WORKDIR /app

COPY . .

RUN npm install

COPY .env.docker .env

EXPOSE 5000

CMD ["npm","start"]
