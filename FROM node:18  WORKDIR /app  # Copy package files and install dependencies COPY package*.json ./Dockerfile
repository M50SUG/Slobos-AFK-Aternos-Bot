FROM node:18

WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of your bot code
COPY . .

# Tell Hugging Face to run your main bot script
CMD ["node", "index.js"]
