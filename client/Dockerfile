FROM node:lts-alpine
RUN mkdir /app
WORKDIR /app
COPY package*.json ./
COPY public public
RUN npm i
COPY src src
# RUN npm run build
CMD npm run start