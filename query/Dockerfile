# Specify a base image
FROM node:14-alpine

# Set work directory
WORKDIR /app

# Copy package.json
COPY ./package.json ./

# Install dependencies
RUN npm install

# Copy remaining files
COPY ./ ./

# Default command
CMD ["npm", "start"]