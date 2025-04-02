FROM node:alpine3.21

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .
ARG PORT_NUMBER=3001
ENV PORT =  ${PORT_NUMBER}
EXPOSE ${PORT_NUMBER}

CMD [ "node", "server.js" ]