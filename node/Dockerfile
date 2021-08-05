FROM node:latest 
MAINTAINER Luiz Fernando de Santana
COPY ./deploy /var/www
WORKDIR /var/www
RUN npm install
ENTRYPOINT npm run start
EXPOSE 3000