FROM node:18-alpine

WORKDIR /docker-react-example

COPY public/ /docker-react-example/public
COPY src/ /docker-react-example/src
COPY package.json /docker-react-example/package.json

RUN npm install

CMD ["npm", "start"]