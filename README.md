# grpc-gopoc


new terminal window run the following command

go install google.golang.org/protobuf/cmd/protoc-gen-go@latest \
  && go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest

 to start the gRPC server
 go run server/main.go

  to execute the gRPC client request
  go run client/main.go
