# Base image
FROM node:18-alpine

# Set working directory
WORKDIR /usr/src/app

# Install project dependencies
COPY ./package.json ./
RUN npm install
RUN npm install -g next

# Expose port and start development server
EXPOSE 3000
CMD [ "npm", "run", "dev" ]