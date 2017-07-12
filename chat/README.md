
# Socket.IO Chat

A simple chat demo for socket.io

## How to use

```
$ cd socket.io
$ npm install
$ cd examples/chat
$ npm install
$ npm start
```

And point your browser to `http://localhost:3000`. 
Here we can replace the URL with the last ip address of our system "10.182.245.200" :
EX: ipconfig

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . : cerner.net
   Link-local IPv6 Address . . . . . : fe80::d12a:dc2:4ac8:2251%9
   IPv4 Address. . . . . . . . . . . : 10.182.245.200
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : 10.182.245.1

Optionally, specify a port by supplying the `PORT` env variable.

## Features

- Multiple users can join a chat room by each entering a unique username
on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves
the chatroom.
