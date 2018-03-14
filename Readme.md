## Installation Instructions

First, clone this repo. Then:

1. docker-compose build web
2. docker-compose up web

now that your server is booted, navigate to http://locahost:8888 and login!
The password to login is the token in your server logs. It's the value after `token=`.
Paste that into the browser to login.

**Note**: Like normal Docker, if you need more packages for your ecosystem, add them to your Dockerfile and then do:

1. docker-compose build web
2. docker-compose up web
