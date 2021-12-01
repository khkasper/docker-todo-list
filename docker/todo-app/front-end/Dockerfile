FROM node:14-alpine
WORKDIR /todo-app
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
RUN  ["npm", "install"]
ENTRYPOINT [ "npm", "start" ]