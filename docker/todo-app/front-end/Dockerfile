FROM node:14-alpine

WORKDIR /app

ADD node_modules.tar.gz /app

COPY . .

EXPOSE 3000

CMD ["npm", "start"]