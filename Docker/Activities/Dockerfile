# Specify Base Image
FROM docker.io/node:18-alpine

# Work Directory
WORKDIR /usr/app

#Copy the package.json
COPY package.json ./

# Install Dependencies
RUN npm install

# COPY Files
COPY ./ ./

# Startup Command
CMD ["npm", "start"]