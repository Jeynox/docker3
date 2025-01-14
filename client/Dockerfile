FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
COPY public public
COPY index.html index.html
COPY vite.config.js vite.config.js
RUN npm i
COPY src src

CMD npm start