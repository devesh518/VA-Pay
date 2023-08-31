FROM node:18.17-alpine3.17

WORKDIR /app/server

COPY package.json .

RUN npm install

COPY . .

CMD ["node", "app.js"]

EXPOSE 3000