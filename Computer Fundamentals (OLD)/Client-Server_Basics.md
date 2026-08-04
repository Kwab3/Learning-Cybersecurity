# Client-Server Basics - 07/29/2026

## What I learned:
- The client-Server Model is the process in which clients communicate with servers
- Hypertext Transfer Protocol or HTTP is a stateless client-server protocol used throughout the world wide web
- The HTTP "GET" command is used to retrieve resources from a web server

## Commands I used:
- GET

## How I solved it:
While GET is a command that runs behind the scenes, I was able to use inspect -> network to get a deeper understanding
of what exactly is going on behind the scenes when the command is run. The main components of information obtained are the
scheme (http/https), host (main website domain), the filename (usually denoted by what comes after the /), address (The Internet Protocol Address of the website), and Status (Whether the request was successful or not)

## Key Takeaways:

A client server model is a way for clients to access information from servers. A request is made and an appropriate response is given by the server be it successful or an error message. Through the protocol used , the client is able to communicate to the server and access whatever the specific server assigned by the port. The DNS gives information regarding the location of the server. HTTP is a protocol that we use throughout the web that is stateless and therefore treats each request like it came from a stranger (which is why things like cookies or identifiers are used). 