# go-gprc-test


# A very basic gRPC Go implementation intended for learning purposes only :)


Generate pb files:
```bash
protoc --go_out=. --go-grpc_out=. --go-grpc_opt=paths=source_relative --go_opt=paths=source_relative greet/greet.proto
``` 