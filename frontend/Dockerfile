FROM node:current-alpine3.18
WORKDIR /user/src/app
COPY package.json package-lock.json ./
RUN npm install
COPY . .