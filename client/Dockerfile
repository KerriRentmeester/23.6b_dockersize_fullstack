# Instructions for slim node image node.js version 14
FROM node:14-slim

# Set work directory "cd /app"
WORKDIR /app

# Copy npm dependencies
COPY package*.json ./

# Install npm dependencies
RUN npm install

# Copy app source code
COPY . .

# Expose port
EXPOSE 3000

# start the app
CMD [ "npm", "start" ]