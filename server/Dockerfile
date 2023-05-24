FROM node:16
LABEL maintainer="Rohan Rustagi"
WORKDIR /app
COPY package-lock.json ./
COPY package.json ./
RUN npm install
RUN npm install connect
RUN npm install st
COPY . .
EXPOSE 5000
CMD [ "npm", "start" ]