# Class 8

* ## Review: High-level HTTP<br/>
HTTP is a protocol which allows the fetching of resources, such as HTML documents. It is the foundation of any data exchange on the Web and it is a client-server protocol, which means requests are initiated by the recipient, usually the Web browser. A complete document is reconstructed from the different sub-documents fetched, for instance text, layout description, images, videos, scripts, and more.
Clients and servers communicate by exchanging individual messages (as opposed to a stream of data). The messages sent by the client, usually a Web browser, are called requests and the messages sent by the server as an answer are called responses.
HTTP is a client-server protocol: requests are sent by one entity, the user-agent (or a proxy on behalf of it). Most of the time the user-agent is a Web browser, but it can be anything, for example a robot that crawls the Web to populate and maintain a search engine index.
---
* ## Java HTTP Request example<br/>
Making HTTP requests is a core feature of modern programming, and is often one of the first things you want to do when learning a new programming language. For Java programmers there are many ways to do it - core libraries in the JDK and third-party libraries. This post will introduce you to the Java HTTP clients that I reach for. If you use other ones, that’s great! Let me know about it.

---