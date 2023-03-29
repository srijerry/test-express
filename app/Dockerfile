FROM node:19.6

WORKDIR /app

COPY /app/package*.json ./
RUN npm install
COPY . ./
EXPOSE 80
CMD node index.js
