FROM node:24-alpine3.20

WORKDIR /app

EXPOSE 3000

COPY package.json package-lock.json ./

RUN npm install --silent

COPY . ./

CMD [ "npm", "start" ]