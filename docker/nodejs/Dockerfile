FROM node:lts-alpine

WORKDIR /app

COPY ./package.json package.json

RUN npm install

COPY . .

ENV PORT=80

EXPOSE 80

CMD ["npm", "start", "dev"]