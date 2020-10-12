# Go SDK for Quorum helloworld plugins

## Quickstart

```
# helloworld plugin sdk
go get github.com/ConsenSys/quorum-hello-world-plugin-sdk-go/proto

# plugin initialization sdk
go get github.com/ConsenSys/quorum-hello-world-plugin-sdk-go/proto_common

# mocks for testing
go get github.com/ConsenSys/quorum-hello-world-plugin-sdk-go/mock_proto
```

## Overview

[Quorum's pluggable architecture](https://docs.goquorum.consensys.net/en/latest/Concepts/Plugins/Plugins/) allows for a Quorum node to be extended with additional functionality.

`helloworld` plugins provide an [example of how to use plugins with Quorum](https://docs.goquorum.consensys.net/en/latest/Concepts/Plugins/Plugins/#example-helloworld-plugin).

The communication between Quorum and a `helloworld` plugin uses gRPC.

This SDK can be used to develop Go `helloworld` plugins that fulfill Quorum's gRPC `helloworld` plugin interface.  It provides the necessary Go types and methods for starting a new gRPC server, initializing a new plugin, and for handling Quorum gRPC requests.

***This repo is auto-updated***

*The [quorum-plugin-definitions](https://github.com/ConsenSys/quorum-plugin-definitions) project defines the `helloworld` plugin gRPC API.  A [GitHub Actions workflow](.github/workflows/run.yml) updates the SDK whenever quorum-plugin-definitions is altered.*
