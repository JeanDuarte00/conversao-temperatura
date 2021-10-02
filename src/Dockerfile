ARG TAG=latest
FROM node:$TAG
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8090
ENTRYPOINT ["node", "server.js"]

#RUN apt-get update && apt-get install npm -y && npm install && node server
