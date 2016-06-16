FROM node:argon

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENTRYPOINT ["node", "server.js"]