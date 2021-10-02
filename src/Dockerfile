ARG TAG=latest
FROM node:$TAG
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8090
CMD ["node", "server.js"]

#RUN apt-get update && apt-get install npm -y && npm install && node server
