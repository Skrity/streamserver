How to use:
1. `wget -O- https://github.com/Skrity/streamserver/archive/refs/heads/master.zip | unzip - ; cd streamserver-master`
2. `docker compose up -d`
3. stream something via obs to rtmp://CONTAINER_IP:1935/app/STREAMKEY
4. watch the stream on http://CONTAINER_IP/app/STREAMKEY


Prerequisites: docker, docker-compose

