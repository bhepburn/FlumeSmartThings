FROM node:15

# Create app directory
WORKDIR /usr/src/app

COPY * ./
RUN npm install

EXPOSE 3006
CMD [ "node", "index.js" ]
