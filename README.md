# Docker image for TURN server
A Docker container with the [Coturn TURN server](https://github.com/coturn/coturn)

forked zolochevska/turn-server

sudo docker run -d -p 3478:3478 -p 3478:3478/udp --restart=always zolochevska/turn-server username password realm
