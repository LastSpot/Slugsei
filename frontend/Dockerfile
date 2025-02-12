FROM node:16-alpine

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install  # Or yarn install if you use yarn

COPY . .

# Expose the port that your development server uses (usually 3000 for React)
EXPOSE 3000

# Start the development server
CMD ["npm", "start"]  # Or yarn start if you use yarn