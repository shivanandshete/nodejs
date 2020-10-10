FROM node:8

CMD mkdir /app && chown -R node:node /app

WORKDIR /app

COPY package*.json ./app

CMD sudo npm install

COPY . .

CMD ["npm","start"]