FROM node:18.17-alpine3.17

WORKDIR /app/client

COPY package.json .

RUN npm install

COPY . .

RUN npm run build

CMD ["npm", "run", "preview"]

EXPOSE 4173