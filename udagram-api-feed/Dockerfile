FROM node:13
# Create app directory

WORKDIR /usr/src/app

# Install dependencies

COPY package*.json ./
RUN npm ci

# Bundle app source
COPY . .
EXPOSE 8080
CMD ["npm", "run", "dev" ]