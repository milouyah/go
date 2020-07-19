# [Golang](https://golang.org/)

## Install
[How To Install Go on Ubuntu 20.04 Focal Fossa Linux](https://linuxconfig.org/how-to-install-go-on-ubuntu-20-04-focal-fossa-linux)

```bash
$ sudo apt install golang
$ go version
sudo apt install golang


# Download Golang hello world example:
$ go get github.com/golang/example/hello
$ cd ~/go
~/go$ ls
bin  src

# Compile hello
$ go install github.com/golang/example/hello
$ ~/go/gin/hello
Hello, Go examples!
```

*** Default gopath : \[USER_HOME\]/go*** 

## Hello.go

```bash
go build hello.go
```

```go
package main

import "fmt"

func main() {
	fmt.Printf("hello, world\n")
}
```


## [filepath](https://golang.org/pkg/path/filepath/)

