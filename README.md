# Basic TELNET in Python

**Individual Projects for ITT440**

Prepared by **Amirul Hakim bin Abdul Rashid (2019685886)**

## This project includes:
- What is Telnet?
- How it works?
- How to use Telnet to remote a Linux computer?
- How to test the connectivity while using Telnet?
- Simple application of socket programming in Python
- Demonstration!

## Link for my video presentation

Youtube:
https://youtu.be/b5Dz3NAQQXc
Google Drive(optional):
https://drive.google.com/file/d/193PSGIIGtEYR5VOhuIqxssoimOQ6FcGf/view?usp=sharing

## Installation of Telnet in Ubuntu/Linux

Simply follow this tutorial
https://www.journaldev.com/28614/telnet-command-linux-unix

## What is Telnet?

Telnet is a network protocol used to virtually access a computer and to provide a two-way, collaborative and text-based communication channel between two machines.
It follows a user command Transmission Control Protocol/Internet Protocol (TCP/IP) networking protocol for creating remote sessions. 

## How it works?

-Telnet uses port 23, which was designed specifically for local area networks
-It helps to connect to a remote Linux computer
-It run programs remotely and conduct administration
-Telnet transfers the data in plain text while in SSH data is sent in encrypted format 
 via a secure channel.
-Comparing telnet vs ssh, ssh is more secure since it is encrypted communication

## Test the connectivity while using Telnet

- Referring to the code **telnet.py**, the purpose is to test the connectivity.
- By using ping command, we can check if the Telnet is connected or not with google. 
- When the connection is established, the server replies will appear on the terminal

## Simple socket programming in Python (ChatRoom Server)

- This program is to create a chat room between multiple user.
- There will be a server that can monitor the chat between the users.
- Every messages is broadcasted to every connected chat users.

**Server**
- Server will accept multiple connection of users
- Read incoming messages, and broadcasted it to every connected clients.

**Client**
- Client will listen to all incoming messages from the server.
- If the user types in a message, then client will send it back to server.

## References

- https://www.guru99.com/telnet-vs-ssh.html
- https://www.howtoforge.com/how-to-install-and-use-telnet-on-ubuntu/
- https://www.binarytides.com/code-telnet-client-sockets-python/
