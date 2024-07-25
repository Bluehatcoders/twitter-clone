FROM node:20.15.1-alpine3.20

WORKDIR /usr/src/web

COPY package.json .
COPY yarn.lock .

RUN yarn

EXPOSE 3000

CMD ["yarn", "dev"]