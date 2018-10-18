# Yojik-docker

Docker build for the [Yojik](https://github.com/thomasylee/yojik) XMPP server.

# Building

`docker build . -t yojik-dev`

# Running

`docker run --rm --name yojik -p 5222:5222/tcp -d tomyl/yojik`

The server will be listening on port 5222 for incoming TCP connections.
