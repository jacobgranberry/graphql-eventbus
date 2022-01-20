<p align="center"><img src="website/static/img/logo-large.png" width="200"/></p>

# GraphQL Eventbus

> Build a GraphQL powered Event architecture

## Overview

GraphQL eventbus is an abstraction layer on top of GraphQL SDL to publish and consume messages in a type-safe way. It is message broker agnotic: you can use Kafka, RabbitMQ, Google Pubsub or any other message broker. With features like code generation, API evolution without breaking changes, plugin system for logging and monitoring, and more, you can build a production quality event hub for your service architecture.

## Features

- ✂️ **Schema Driven:** Define your events and payloads in GraphQL schema. Consume your events using GraphQL documents.
- 🤝 **Message Broker agnostic:** Works with any message broker. We provide packages for Google Pubsub and RabbitMQ. You can easily use the library to build a bus for your message broker.
- 🚀 **Code Generation:** <a href="https://www.graphql-code-generator.com/">GraphQL Codegen</a>{" "}
  plugin to generate code for typescript.
- 🎯 **Plugins:** We provide plugins for logging and monitoring. You can also build your custom plugins.
- 🤖 **Testing Utilities:**: The library comes with utilities to easily sample payload for your events and test your event handlers.

## Documentation

You can find extensive documentation at [https://graphql-eventbus.vercel.app](https://graphql-eventbus.vercel.app).

## Contributing

We are always looking for people to help us grow `graphql-eventbus`! If you have an issue, feature request, or pull request, let us know!

## License

MIT @ Suraj Keshri
