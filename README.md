# Docker

$ docker build -t <docker-hub-username>/feedback .

$ docker run -itd --name webserver --publish 8080:80 <docker-hub-username>/feedback
