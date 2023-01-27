FROM node:16-alpine

WORKDIR /contact

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "npm", "run", "serve" ]

