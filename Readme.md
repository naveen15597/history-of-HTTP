# History of HTTP
The Hypertext Transfer Protocol (HTTP) is one of the most ubiquitous and widely adopted application protocols on the Internet: it is the common language between clients and servers, enabling the modern web. From its simple beginnings as a single keyword and document path, it has become the protocol of choice not just for browsers, but for virtually every Internet-connected software and hardware application.

## HTTP 0.9: The One-Line Protocol
Features:
1.Client-server, request-response protocol.
2.ASCII protocol, running over a TCP/IP link.
3.Designed to transfer hypertext documents (HTML).
4.The connection between server and client is closed after every request.

## HTTP/1.0: Rapid Growth and Informational RFC
Features:
1.Request may consist of multiple newline separated header fields.
2.Response object is prefixed with a response status line.
3.Response object has its own set of newline separated header fields.
4.Response object is not limited to hypertext.
5.The connection between server and client is closed after every request.

## HTTP/1.1: Internet Standard
Features:
1.Request for HTML file, with encoding, charset, and cookie metadata
2.Chunked response for original HTML request
3.Number of octets in the chunk expressed as an ASCII hexadecimal number (256 bytes)
4.End of chunked stream response
5.Request for an icon file made on same TCP connection
6.Inform server that the connection will not be reused
7.Icon response, followed by connection close

## HTTP/2: Improving Transport Performance
The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypermedia information systems. It is a generic, stateless, protocol that can be used for many tasks beyond its use for hypertext, such as name servers and distributed object management systems, through extension of its request methods, error codes and headers. A feature of HTTP is the typing and negotiation of data representation, allowing systems to be built independently of the data being transferred.
