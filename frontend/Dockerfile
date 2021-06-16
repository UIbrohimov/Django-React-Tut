FROM node:14.4.0-alpine3.10

RUN mkdir /frontend

WORKDIR /frontend

COPY . /frontend

RUN yarn install

RUN yarn build