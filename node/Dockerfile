FROM node:latest 
MAINTAINER Luiz Fernando de Santana
COPY ./deploy /var/www
ENV PORT=3000
WORKDIR /var/www
RUN npm install
ENTRYPOINT npm run start
EXPOSE $PORT