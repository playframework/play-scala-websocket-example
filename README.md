[![Travis](https://img.shields.io/travis/playframework/play-scala-websocket-example.svg?style=flat)](https://travis-ci.org/playframework/play-scala-websocket-example) [![GitHub issues](https://img.shields.io/github/issues/playframework/play-scala-websocket-example.svg?style=flat)](https://github.com/playframework/play-scala-websocket-example/issues) [![GitHub forks](https://img.shields.io/github/forks/playframework/play-scala-websocket-example.svg?style=flat)](https://github.com/playframework/play-websocket-java/network) [![GitHub stars](https://img.shields.io/github/stars/playframework/play-scala-websocket-example.svg?style=flat)](https://github.com/playframework/play-scala-websocket-example/stargazers)

# play-websocket-scala-example

This is an example Play application that shows how to use Play's Websocket API in Scala, by showing a series of stock tickers updated using WebSocket.

The Websocket API is built on Akka Streams, and so is async, non-blocking, and backpressure aware.  Using Akka Streams also means that interacting with Akka Actors is simple.

There are also tests showing how ScalaTest and Akka Testkit are used to test actors and flows.

For more information, please see the documentation for Websockets and Akka Streams:

* https://www.playframework.com/documentation/latest/ScalaWebSockets
* http://doc.akka.io/docs/akka/current/scala/stream/stream-flows-and-basics.html#stream-materialization
* http://doc.akka.io/docs/akka/current/scala/stream/stream-integrations.html#integrating-with-actors
