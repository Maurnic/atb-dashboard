# We need to build shit here

FROM node:18-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install --silent

COPY . .

EXPOSE 3000

# Build the Next.js app
RUN npm run build

# Start the app
CMD ["npm", "run", "dev"]