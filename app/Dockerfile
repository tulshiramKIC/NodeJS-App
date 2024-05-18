FROM node:20

WORKDIR /usr/src/app

COPY app/package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]
