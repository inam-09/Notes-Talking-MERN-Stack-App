# Base image
FROM node:lts-bookworm-slim

# Working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy remaining files
COPY . .

# Expose port
EXPOSE 4002

# Start server
CMD ["npm", "start"]
