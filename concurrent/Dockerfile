# FROM node:16
FROM node:20.3.0

WORKDIR /usr/app

COPY package*.json ./

RUN yarn install --frozen-lockfile

COPY . .

CMD [ "yarn", "start" ]
