##Using WebSocket to build an interactive web application

This guide walks you through the process of creating a "hello world" application that sends messages back and forth, between a browser and the server. WebSocket is a very thin, lightweight layer above TCP. It makes it very suitable to use "subprotocols" to embed messages. In this guide we’ll dive in and use STOMP messaging with Spring to create an interactive web application.

[Spring Getting Started](https://spring.io/guides/gs/messaging-stomp-websocket/)

###What you’ll build

You’ll build a server that will accept a message carrying a user’s name. In response, it will push a greeting into a queue that the client is subscribed to.

####What you’ll need

* About 15 minutes
* A favorite text editor or IDE
* JDK 1.7 or later
* Gradle 2.3+ or Maven 3.0+
* You can also import the code from this guide as well as view the web page directly into Spring Tool Suite (STS) and work your way through it from there.
