### GOLANG Base setup

### this is path of workspace, you can change to your workspace path - This allows to use sub folder path from go.mod as refrence 
export GOPATH=~/go/src/github.com/pankajojha  
 

### Swagger UI setup for Go API using Swaggo

Sample code for swagger documention generation for Go API using Swaggo. This codebase is built upon [go-orders-api] by adding swagger specific libraries and annotations.

***
### Setup and usage
```
cd to the project directory
```

```go
go build swag-api
./swag-api
```

``` make
make build 
make run
```


Navigate to http://localhost:8080/swagger/index.html in your browser and check out the Swagger UI.
# swag-test
