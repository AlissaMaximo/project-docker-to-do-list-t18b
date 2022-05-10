FROM node:16-alpine

WORKDIR /docker/todo-app/tests

RUN npm install

COPY . .

EXPOSE 3000

CMD npm start