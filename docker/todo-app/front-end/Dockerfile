FROM node:14

EXPOSE 3000

ADD node_modules.tar.gz ./

WORKDIR /docker/todo-app/front-end

ENTRYPOINT [ "npm start" ]
