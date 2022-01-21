FROM node:14-alpine
WORKDIR /tests
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm test" ] 

