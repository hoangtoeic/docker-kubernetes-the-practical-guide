FROM node:12

WORKDIR /APP

COPY package.json ./

RUN npm install

COPY . ./

EXPOSE 80

CMD ["node", "server.js"]
