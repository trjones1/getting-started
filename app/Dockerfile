# syntax=docker/dockerfile:1
FROM node:12-alpine
COPY package.json yarn.lock ./
RUN yarn install --production
COPY . .
CMD ["node", "src/index.js"]