FROM node:18-buster

WORKDIR /app

COPY package.json package-lock.json /app/

RUN npm install

COPY ./src /app/src/

EXPOSE 3000

CMD ["npm", "start"]