FROM node:14-alpine
WORKDIR /docker/todo-app/front-end

COPY . .

RUN npm install

ADD node_modules.tar.gz .

EXPOSE 3000

CMD ["npm", "start"]
