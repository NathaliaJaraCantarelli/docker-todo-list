FROM node:14-alpine

EXPOSE 3001

ADD node_modules.tar.gz ./

WORKDIR /docker/todo-app/back-end

ENTRYPOINT ["npm start"]