FROM node:14-alpine AS todofrontend

WORKDIR /todo-app/front-end

ADD node_modules.tar.gz .

EXPOSE 3000

COPY . .

ENTRYPOINT ["npm", "start"]
