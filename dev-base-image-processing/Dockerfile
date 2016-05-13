FROM siomiz/node-opencv:latest

RUN sudo apt-get update && sudo apt-get install imagemagick\
  && npm install nodemon -g 

WORKDIR /src

ENV NODE_ENV=development

CMD nodemon -L