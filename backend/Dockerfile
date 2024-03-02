FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . ./

EXPOSE 8022

CMD ["npm", "start"]