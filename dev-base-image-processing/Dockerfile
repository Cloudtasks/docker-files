FROM siomiz/node-opencv:latest

RUN apt-get update && apt-get install imagemagick\
  && npm install nodemon -g 

WORKDIR /src

ENV NODE_ENV=development

CMD nodemon -L