FROM node:16-alpine

WORKDIR /app

COPY . .

RUN yarn install

RUN yarn build

CMD [ "node", "dist/main.js" ]