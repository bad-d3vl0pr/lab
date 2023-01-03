# Concurrency in Go with Http Server

Example of how to manage concurrency on a HTTP server with golang

## Commands

```bash
ab -n 10000 -c 100 "127.0.0.1:8000/inc?name=i"
```

## Source

* <https://eli.thegreenplace.net/2019/on-concurrency-in-go-http-servers/>
