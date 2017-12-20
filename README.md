# adonis4-docker
adonisjs v4 with docker, docker-compose, nginx and mysql

# init setup
* docker-compose build
* docker-compose up -d
* docker-compose run adonis4 bash

* adonis new yardstick
* npm install

# db setup
* use mysql workbench to log into your db 
* default values
* ip: 127.0.0.1
* port: 3306
* db: adonis4
* user: not_root
* pass: adonis4

# .env setup 
root .env controls which nginx file to load, default .env will be "dev" you can then make prod.conf etc

# nginx
Make an entry in your hosts file e.g. 127.0.0.1 example.dev, then update config/dev.conf with your nginx server block
