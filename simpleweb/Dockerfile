# Specify a base image

FROM node:alpine

# Needed for new npm version

WORKDIR /usr/app

# Install some dependencies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]
