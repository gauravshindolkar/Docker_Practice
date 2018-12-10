#Specify a base image
FROM node:alpine


WORKDIR /usr/app

#install some dependencies
COPY ./package.json ./  #if only one file change
RUN npm install
COPY ./ ./

#Defaullt command
CMD ["npm", "start"]