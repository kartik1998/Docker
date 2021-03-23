FROM node

WORKDIR /app
COPY package.json .
RUN npm install --silent
COPY . .
EXPOSE 80
CMD ["node", "app.js"]
