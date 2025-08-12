# testproxy
Test reverse proxy

To build:
docker build -t testproxy:1.0 .

To run:
docker run -d --network host --name testproxy testproxy:1.0