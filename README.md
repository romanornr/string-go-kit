# string-go-kit
Trying out go-kit


$ curl -d '{"s": "Hello, World!"}' http://localhost:8080/count
{"v":13}

$ curl -d '{"s": "Hello, World!"}' http://localhost:8080/uppercase
{"v": "HELLO, WORLD!"}
