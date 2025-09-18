# Use Node.js lightweight base image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy frontend source code
COPY . .

# Expose frontend port
EXPOSE 3000

# Start frontend
CMD ["npm", "start"]
