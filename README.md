# Open API

Design API without implementation.

## Swagger Hub

Test open API online [Swagger Link](https://app.swaggerhub.com/apis/nuxzero/sample-store/1.0.0)

## Local

This project used [apisprout](https://github.com/danielgtaylor/apisprout) to run Open API in local.

**Install GO** 
```
brew install go
```

**Set GOPATH**
```
export GOPATH=$HOME/go
export PATH=$GOPATH/bin:$PATH
```

**Install Apisprout** \
```
go get github.com/danielgtaylor/apisprout
```

## Usage

`apisprout --validate-server --watch sample-store.yml`

Now you can test API from this URL

`http://localhost:8000/nuxzero/sample-store/1.0.0/[API_PATH]`

## References
- [Swagger](https://swagger.io/docs/specification/about/)
- [API Sprout](https://github.com/danielgtaylor/apisprout)