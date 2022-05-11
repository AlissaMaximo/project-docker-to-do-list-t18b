FROM node:16-alpine

WORKDIR /docker/todo-app/front-end

RUN npm install

COPY . .

ADD node_modules.tar.gz .

EXPOSE 3000

CMD ["npm", "start"]
