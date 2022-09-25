# gRPC Training: [The Complete Guide](https://dev.to/techschoolguru/series/7311)

## Useful Links:

https://developers.google.com/protocol-buffers/docs/reference/go-generated
https://dev.to/techschoolguru/how-to-define-a-protobuf-message-and-generate-go-code-4g4e
https://towardsdev.com/option-go-package-in-protobuf-a0fd0d71ab21


```go
protoc --proto_path=./proto --go_out=./pb --go_opt=paths=source_relative processor_message.proto 
```

