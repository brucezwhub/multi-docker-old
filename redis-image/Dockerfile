#use an existing docker image as a base
#alpine: 
FROM alpine

#download and install dependency
RUN apk add --update gcc
RUN apk add --update redis

# tell the image what to do when it starts
# as a container
CMD ["redis-server"]
