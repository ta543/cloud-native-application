FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy application code
COPY . .

# Expose port (replace 3000 with your service port)
EXPOSE 3000

# Command to run the service
CMD ["npm", "start"]
