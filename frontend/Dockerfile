FROM node:20-alpine

WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy source code
COPY . /app

EXPOSE 5173

CMD ["npm", "start"]