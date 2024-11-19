FROM node:latest AS base
WORKDIR /app
ADD ./package.json ./
ADD ./src/app.js ./src/app.js

RUN npm install

CMD ["npm", "start"]
