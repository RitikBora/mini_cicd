FROM node:alpine

WORKDIR ./backend

COPY ./package*.json /backend

RUN yarn

COPY . .

EXPOSE 3000

CMD ["npm" , "run" , "dev"]
