FROM node:20

WORKDIR /backend

COPY package*.json ./

RUN npm install

COPY .env ./

COPY . .

EXPOSE 3001

CMD ["node", "serveur.js"]