# productinfo

### Skeleton generation
    cd service
    protoc ecommerce/product_info.proto --go_out=./ecommerce --go-grpc_out=./ecommerce

    cd client
    protoc ecommerce/product_info.proto --go_out=./ecommerce --go-grpc_out=./ecommerce

### Building Server and Client
    cd service
    go build -v -o bin/server

    cd client
    go build -v -o bin/client

### Running Server and Client
    cd service
    ./bin/server

    cd client
    ./bin/client
