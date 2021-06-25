FROM node:15-buster
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 3000/tcp
CMD ["npm", "start"]

