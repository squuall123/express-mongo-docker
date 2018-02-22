FROM node:9

RUN npm install -g nodemon

RUN mkdir /src

WORKDIR /src

ADD package.json /src/package.json

RUN npm install

EXPOSE 3000

CMD npm start
