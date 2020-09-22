FROM node:13.8.0-alpine3.11

RUN apk update 
RUN apk add git 
RUN apk add openssh

# RUN mkdir /.ssh

# ADD id_rsa /.ssh/id_rsa

# RUN touch /.ssh/known_hosts

# RUN echo -e "Host github.com\n\tStrictHostKeyChecking no\n" >> /.ssh/config

# RUN git clone git@github.com:rwithers/spotform.git 

# change this to curl the zip / tar download from the repo 

EXPOSE 3050:3050

WORKDIR /

ENTRYPOINT ["node", "/app.js"]
