FROM node:16-alpine

WORKDIR /docker/todo-app/tests

COPY . .

RUN npm install

ADD node_modules.tar.gz .

EXPOSE 3000

CMD ["npm", "start"]
