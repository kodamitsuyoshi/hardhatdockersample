FROM node:16.3-alpine

RUN apk update && \
apk add git python3 make g++

RUN yarn install && yarn add -D \
    hardhat

WORKDIR /hardhat_contracts

