# go-gprc-test
Intended for leaning


Generate pb files:
```bash
protoc --go_out=. --go-grpc_out=. --go-grpc_opt=paths=source_relative --go_opt=paths=source_relative greet/test.proto
``` 