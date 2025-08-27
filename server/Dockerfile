# Backend (Node/Express)
FROM node:22-alpine

# Set workdir
WORKDIR /app

# Copy package files and install
COPY package*.json ./
RUN npm install

# Copy source code
COPY . .

# Expose server port
EXPOSE 3000

# Run backend
CMD ["npm", "run", "dev"]
