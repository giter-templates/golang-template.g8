# $name$

## Setup
```shell
go mod init $name$
```

## Run
```shell
go run .
```

## Test
```shell
go test .
```

## Format
```shell
gofmt .
```

## Install dependencies
```shell
go mod tidy
```

## Compile and install the application
```shell
go build
./$name$
``` 

## Docker
```shell
docker build -t $name$ .
docker run --rm $name$:latest
```