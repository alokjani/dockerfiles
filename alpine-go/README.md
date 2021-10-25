# Golang Docker Image

Go Image with Alpine.

## Usage

    $ echo -e 'package main; import "fmt"; func main() { fmt.Println("Hello World") }' > qq.go
    $ docker run --rm -v `pwd`:/tmp alokjani/alpine-go go run /tmp/qq.go