FROM node:14

EXPOSE 3000

WORKDIR /user

ADD node_modules.tar.gz ./

COPY . .

ENTRYPOINT ["npm", "start"]
