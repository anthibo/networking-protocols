## UDP server with node.js

Implemented a simple UDP server that gets clients messages and print the messages with clients addresses.
Used datagram module to create a udp socket.
## Run Locally

Clone the project



Go to the project directory

```bash
  cd udp-server-node
```

Start the server

```bash
  npm run start
```

Connect to the udp server and send a message:

```bash
nc -u 127.0.0.1 5500
Anthibo is here
```

Server output:
```
My server got a datagram Anthibo is here
, from: 127.0.0.1:42746
```

