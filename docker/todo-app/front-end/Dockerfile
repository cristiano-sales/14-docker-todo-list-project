FROM node:14-alpine AS todofrontend

WORKDIR /docker

ADD node_modules.tar.gz ./

COPY . .

CMD [ "npm", "start" ]

EXPOSE 3000
