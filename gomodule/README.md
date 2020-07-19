# go-module
## [Using Go Modules](https://blog.golang.org/using-go-modules)

### Creating a new module

1. create hello.go
2. create hello_test.go
3. test

```
$ go test
PASS
ok      github.com/milouyah/go/gomodule 0.001s
```

```
$ go mod init github.com/milouyah/hello
go: creating new go.mod: module github.com/milouyah/hello

$ go test
PASS
ok      github.com/milouyah/hello       0.001s

$ cat go.mod
module github.com/milouyah/hello

go 1.13
```