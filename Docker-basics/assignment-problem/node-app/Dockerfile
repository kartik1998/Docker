FROM node:latest

WORKDIR /app
COPY package.json .
RUN npm install --silent
COPY . .

CMD ["node", "server.js"]
