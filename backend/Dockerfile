FROM node:14

WORKDIR /Docker_Nginx_Nodejs/backend

COPY package*.json ./
RUN npm install

COPY . .
CMD [ "node", "index.js" ]