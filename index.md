---
layout: default
---

# Getting Started gRPC in Dart
![gRPC](https://grpc.io/img/landing-3.svg)

gRPC, the modern, lightweight communication protocol from Google. It’s a high-performance, open-source universal remote procedure call (RPC) framework that works across a dozen languages running in any OS.

## Install Protocol Buffers v3

- Download protoc compiler from Github for your OS (`protoc-<version>-<os>.zip`)
- Unzip the resource and add its directory into environment PATH, for example in `~/.bash_profile` append line 
  ```
  export PATH=”$PATH:/Users/putraxor/Dev/protoc-3.6.1-osx-x86_64/bin”
  ```
- Next, install the protoc plugin for Dart
  ```
  pub global activate protoc_plugin
  ```
- Add protocol compiler to your PATH
  ```
  export PATH=$PATH:$HOME/.pub-cache/bin
  ```
- Try to generate stubs from this repository https://github.com/grpc/grpc-dart/tree/master/example/googleapis