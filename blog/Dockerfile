FROM node:16.14-alpine

WORKDIR /blog

COPY package* ./

RUN npm install

EXPOSE 8080

COPY . .

ENTRYPOINT [ "npm", "run" ]

CMD [ "dev" ]