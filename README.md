# Hello gin-jwt

The project is clone the example from [gin-jwt](https://github.com/appleboy/gin-jwt)

## Run

```
go run .
```

## Test login api

### Use [httpie](https://github.com/httpie/httpie) CLI HTTP client.

```
$ brew install httpie
$ http -v --json POST localhost:8000/login username=admin password=admin
```
### Use httpie extension in vscode

- Install httpie
- Install httpie extension
- Send request by [request.httpie](./request.httpie) in vscode


## Reference
- [gin-jwt](https://github.com/appleboy/gin-jwt)