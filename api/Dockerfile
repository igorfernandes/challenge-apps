FROM node:latest

COPY . /app

WORKDIR /app

RUN npm install
RUN rm -f .npmrc

CMD [ "npm", "start" ]
