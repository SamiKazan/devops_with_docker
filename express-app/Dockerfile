FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

# 5. Start your app
CMD ["node", "index.js"]