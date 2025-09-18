# frontend/Dockerfile
FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .   # <-- this copies public/ and src/ into the container

CMD ["npm", "start"]
