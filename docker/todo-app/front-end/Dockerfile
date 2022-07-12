FROM node:14-alpine
EXPOSE 3000
WORKDIR /home/node/app
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "start" ]