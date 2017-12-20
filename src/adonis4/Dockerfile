FROM node:latest

# Install node modules
RUN npm install -g nodemon

RUN npm i -g @adonisjs/cli

# Create app directory
RUN mkdir -p /usr/src/app/admin
WORKDIR /usr/src/app/admin

ONBUILD RUN npm install

ENV HOST 0.0.0.0
# Install app dependencies
EXPOSE 8080
CMD [ "npm", "run", "dev"]

