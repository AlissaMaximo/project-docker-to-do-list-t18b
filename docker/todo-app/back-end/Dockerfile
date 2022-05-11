FROM node:14-alpine AS todobackend

WORKDIR /docker/todo-app/back-end

COPY . .

RUN npm install

ADD node_modules.tar.gz .

EXPOSE 3001

CMD ["npm", "start"]
