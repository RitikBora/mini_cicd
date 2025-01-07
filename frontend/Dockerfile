FROM node:alpine

WORKDIR ./frontend

COPY ./package*.json /frontend

RUN yarn 

COPY . .

EXPOSE 5173

CMD ["npm", "run", "dev"]
