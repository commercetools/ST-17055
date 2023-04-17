# FROM node:16
FROM node:19.9.0

WORKDIR /usr/one

COPY package*.json ./

RUN yarn install --frozen-lockfile

COPY . .

CMD [ "yarn", "one" ]
