FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGO_USERNAME=hoang
ENV MONGO_PASSWORD=14121999aA*

CMD ["npm", "start"]