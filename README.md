# Chat based on gRPC

Project `grpchat` - simple server/client chat based on gRPC
, Protocol Buffers with golang for server side and Vue, Typescript, gRPC-web, Stylus and Cypress for client side.
Feel free to try [demo](https://enfipy.github.io/grpchat/)

## Usage:

To begin development:

```
docker-compose up --build
```

## Project:

Project structure:

```
.
├── schema/ - proto files + generated code by protoc
├── envoy/ - envoy proxy config + dockerfile
├── client/ - vue frontend
└── server/ - go backend
```

## Todo:

1. Add authentication
2. Write `cypress` tests
3. Fix demo username release

## Links:

Read about protobuf [here](https://developers.google.com/protocol-buffers/)

What is [gRPC](https://grpc.io)?
