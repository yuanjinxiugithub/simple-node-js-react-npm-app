FROM node:latest
WORKDIR /app

COPY . .

RUN npm install  && npm run build 

RUN  npm install -g serve


CMD serve build