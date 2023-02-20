# FROM node:16
FROM node:19.6.1

WORKDIR /usr/app

COPY package*.json ./

RUN yarn install --frozen-lockfile

COPY . .

CMD [ "yarn", "start" ]
