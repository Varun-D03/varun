# Use an official Node.js runtime as the base image
FROM node:14

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]
