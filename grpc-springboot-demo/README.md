# grpc spring boot demo

> grpc spring boot demo 是基于 [grpc-spring-boot-starter](https://github.com/yidongnan/grpc-spring-boot-starter) 的实例


## 项目结构

* local-grpc-server 服务端
* local-grpc-client 客户端
* local-grpc-proto  公共的pb文件及生成的java类

## Build

1. mvn clean package
2. run GrpcServerApplication
3. run GrpcClientApplication
4. curl http://localhost:8080/api/user?userId=1

