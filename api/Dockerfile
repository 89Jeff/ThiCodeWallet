
FROM node:latest

WORKDIR /api

COPY . .

RUN rm-rf node_modules
RUN npm i

CMD ["nmp", "start"]

EXPOSE 5002