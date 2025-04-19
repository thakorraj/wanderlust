FROM node:latest

WORKDIR /app

COPY . .

RUN npm install

COPY .env.docker .env.local

EXPOSE 5173

CMD ["npm","run","dev","--","--host"]
