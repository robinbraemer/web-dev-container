Docker PHP-FPM 7.1 & Nginx 1.12 on Alpine Linux with SSH login
==============================================
Example PHP-FPM 7.1 & Nginx 1.12 setup for Docker, build on [Alpine Linux](http://www.alpinelinux.org/).
The image is only +/- 35MB large.


[![Docker Pulls](https://img.shields.io/docker/pulls/roboflax/web-dev.svg)](https://hub.docker.com/r/roboflax/web-dev/)

Usage
-----
Start the Docker containers:

    docker run -d -p 2221:22 -p 8321:80 -p 4443:443 --name "web_dev" -m=2048MB roboflax/web-dev:1.2

See the the static html page on http://localhost:8321/test.html

Login to SSH:

user: root
password: root

brilliant right?
