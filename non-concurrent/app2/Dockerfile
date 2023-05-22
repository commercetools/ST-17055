# FROM node:16
FROM node:20.2.0

WORKDIR /usr/two

COPY package*.json ./

RUN yarn install --frozen-lockfile

COPY . .

CMD [ "yarn", "two" ]
