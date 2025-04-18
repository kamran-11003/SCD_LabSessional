FROM node:18-alpine
WORKDIR /
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3004
CMD ["node", "index.js"]
