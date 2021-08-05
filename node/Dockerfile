FROM node:latest 
MAINTAINER Luiz Fernando de Santana
ENV PORT=3000
WORKDIR /var/www
RUN npm install
ENTRYPOINT npm run start
EXPOSE $PORT