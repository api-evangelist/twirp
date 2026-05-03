# Twirp

Twirp is a simple RPC framework built on Protocol Buffers, created by Twitch, that generates routing and serialization code from Protobuf service definitions for Go and other languages. Similar to gRPC but runs on the standard library's net/http server without custom transport implementations.

**Type:** Company (Open Source)  
**License:** Apache 2.0  
**Modified:** 2026-05-03

## Framework

### Twirp RPC Framework
Define your service in a .proto file and Twirp generates servers and clients implementing the Twirp wire protocol over HTTP. Uses POST requests with URLs in the form /twirp/[Package].[Service]/[Method]. Supports both Protobuf binary and JSON encoding.

**Human URL:** [https://twitchtv.github.io/twirp/](https://twitchtv.github.io/twirp/)

#### Tags

Protocol Buffers, RPC, Go, Code Generation

#### Properties

- [Documentation](https://twitchtv.github.io/twirp/docs/intro.html)
- [Getting Started](https://twitchtv.github.io/twirp/docs/install.html)
- [GitHub](https://github.com/twitchtv/twirp)
- [Wire Protocol](https://github.com/twitchtv/twirp/blob/main/PROTOCOL.md)

## Artifacts

### JSON Schemas

- [Twirp Error Schema](json-schema/twirp-error-schema.json)

### JSON Structures

- [Twirp Error Structure](json-structure/twirp-error-structure.json)

### JSON-LD

- [Twirp Context](json-ld/twirp-context.jsonld)

### Vocabulary

- [Twirp Vocabulary](vocabulary/twirp-vocabulary.yml)

## Common Properties

- [Website](https://twitchtv.github.io/twirp/)
- [Documentation](https://twitchtv.github.io/twirp/docs/intro.html)
- [GitHub Organization](https://github.com/twitchtv)
- [GitHub Repository](https://github.com/twitchtv/twirp)
- [Wire Protocol](https://github.com/twitchtv/twirp/blob/main/PROTOCOL.md)
- [License](https://github.com/twitchtv/twirp/blob/main/LICENSE)

## Tags

Protocol Buffers, RPC, Go, SDKs, Open Source, Protobuf

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
