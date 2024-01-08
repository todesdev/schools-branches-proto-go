# Protobuf Locations

```shell
protoc --proto_path=. \
  --go_out=./branches --go_opt=paths=source_relative \
  --go-grpc_out=./branches --go-grpc_opt=paths=source_relative \
  branches.proto
```