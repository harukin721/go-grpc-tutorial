# go-grpc-tutorial

[Go | gRPC](https://grpc.io/docs/languages/go/) やる

## Run the example

gRPC を使用してクライアント サーバー アプリケーションを実行

```bash
~/ghq/github.com/harukin721/go-grpc-tutorial/grpc-go/examples/helloworld (git)-[tags/v1.76.0]
% go run greeter_server/main.go
go: downloading google.golang.org/genproto/googleapis/rpc v0.0.0-20250804133106-a7a43d27e69b
go: downloading golang.org/x/net v0.42.0
go: downloading golang.org/x/sys v0.34.0
go: downloading google.golang.org/genproto v0.0.0-20250804133106-a7a43d27e69b
go: downloading golang.org/x/text v0.27.0
2025/11/10 12:45:32 server listening at [::]:50051
2025/11/10 12:46:35 Received: world
```

```bash
~/ghq/github.com/harukin721/go-grpc-tutorial/grpc-go/examples/helloworld (git)-[tags/v1.76.0]
% go run greeter_client/main.go
2025/11/10 12:46:35 Greeting: Hello world
```

## Basics tutorial


