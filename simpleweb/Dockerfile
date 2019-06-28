#use an existing docker image as a base
#specify version
FROM node:alpine

#download and install dependency
#RUN apk add --update gcc
#RUN apk add --update redis
#RUN apk add --update npm
WORKDIR /usr/app

copy ./package.json ./

RUN npm install

copy ./ ./

# tell the image what to do when it starts
# as a container
CMD ["npm", "start"]
