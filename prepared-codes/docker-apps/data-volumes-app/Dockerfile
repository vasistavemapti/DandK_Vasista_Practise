FROM node:alpine3.21

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .
# ARG DEFAULT_PORT=80
# ENV PORT ${DEFAULT_PORT}
# ENV PORT=3000   
EXPOSE 3001

CMD [ "node", "server.js" ]