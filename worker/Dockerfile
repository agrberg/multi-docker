FROM node:alpine
WORKDIR /app
COPY ./package*.json ./
RUN npm install --silentnpm install
COPY . .
CMD ["npm", "run", "start"]
