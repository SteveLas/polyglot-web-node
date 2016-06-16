FROM node:argon

WORKDIR /app

# Configure the listening port to 80
ENV PORT 80
EXPOSE 80

COPY package.json .

RUN npm install

COPY . .

ENTRYPOINT node server.js