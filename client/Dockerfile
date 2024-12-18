FROM node:lts-alpine

WORKDIR /app
COPY package*.json ./
RUN npm i
COPY src src
COPY public public
COPY index.html index.html
COPY vite.config.js vite.config.js


CMD npm start