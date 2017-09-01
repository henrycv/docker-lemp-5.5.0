##
## Name: docker-lamp-vidriera
## Dockerfile to build a LAMP and Node stack image
## Author: https://about.me/henrycv
##
FROM node:8

MAINTAINER Henry Carbajal <entidad.estelar@gmail.com>

# Setted fix to issue "debconf: unable to initialize frontend: Dialog"
# http://askubuntu.com/questions/506158/unable-to-initialize-frontend-dialog-when-using-ssh
ENV DEBIAN_FRONTEND noninteractive

# Install app dependencies
RUN npm install -g grunt grunt-cli bower --save-dev