FROM mhart/alpine-node:latest

RUN apk --update add make git gcc g++ \
	&& npm install nodemon -g

WORKDIR /src

ENV NODE_ENV=development

CMD nodemon -L